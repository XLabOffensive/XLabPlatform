# XLabPlatform


## Grant Proposal

### Problems to address:

The XLabPlatform project aims to answer or address the following questions and problems:

1. Can LLMs be used to efficiently overcome the antivirus protection?
2. Can LLMs be used to find new ways to break user's expirience of using desktop operating systems without priveleges excalation?
3. Can LLMs be used for robotic control of the desktop operating systems

### Methodologies and Approaches:

- LLM
- RPA
- Code Generation
- Distributed LLM Inference

### Expected Results:

 - LLM powered cross platform self modifying virus

# README

a windows/mac application that uses LLM to continuously rewrite its own code and to orchestrate execution of its multiple instances in p2p fashion

intended to be used as a test target for modern anti virus applications

relies on [XCloudPlatform](https://github.com/xcloudplatform)[X](https://github.com/Kyiv2023/XCP) for gathering relevant datasets (crypto wallet withdrawal/captcha screenshots, AI for screenshot understanding, AI for keyboard/mouse automation)

## Plug-ins

### [HumanLog](https://github.com/xcloudplatform/HumanLogger)

logs human activity remotely leveraging XCloudPlatform



### AVLog
 
observe and log the activities of various anti-viruses


### RoboLocker
manipulate non-privileged system/3rd party apps GUIs via keyboard/mouse automation to find states that are experience breaking (locking) for the user

### ScreenSpoofer

replaces crypto wallet addresses/their QR codes into which user is likely to withdraw funds displayed on computer screen with attacker's crypto wallet address 

### ClipboardSpoofer

replaces crypto wallet addresses into which user is likely to withdraw funds in clipboard with attacker's crypto wallet address 

### CaptchaSolver

solves captcha


### distributed llm inference 

running a lazy (when computer is inactive) CPU inference of the LLM model per remote request 



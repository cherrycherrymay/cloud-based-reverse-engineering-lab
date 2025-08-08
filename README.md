# Reverse Engineering Lab (AWS + FlareVM)

A cloud-hosted reverse engineering environment deployed on **AWS** for malware analysis and software reverse engineering personal practice.  
This project was built while following a tutorial by Grant Collins to set up FlareVM in a secure AWS instance. 

## About
This lab provides a controlled, isolated environment for:
- Analyzing malicious software samples.
- Practicing reverse engineering techniques.
- Understanding malware behavior in a safe sandbox.

⚠️ **Disclaimer:** All included malware samples and reverse-engineered software are for educational and research purposes only. Do **not** run them outside an isolated lab environment.

## Features
- Deployable on AWS with minimal setup.
- Tools for disassembly, debugging, and memory analysis.
- Dedicated folder for:
  - Software I have reverse engineered.
  - Malware I have developed for study purposes.

## Installation & Deployment
1. **Deploy on AWS**  
   - Launch a Windows instance in AWS.  
   - Follow Grant Collins' tutorial to set up FlareVM (link in the [Credits](#credits) section).  

2. **Access Your Lab**  
   - Connect via RDP to the AWS instance.  
   - Ensure all network isolation and security groups are configured.

## Usage
- Use FlareVM tools (x64dbg, IDA Free, Ghidra) to inspect binaries.
- Document findings for future reference.

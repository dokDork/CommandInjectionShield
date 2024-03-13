# SiteSniper
[![License](https://img.shields.io/badge/license-MIT-_red.svg)](https://opensource.org/licenses/MIT)  
<img src="https://github.com/dokDork/CommandInjectionShield/raw/main/images/CommandInjectionGuard.jpeg" width="250" height="250">  
  
## Description
**CommandInjectionScript** is a script created to automate a specific penetration test phase: the command injection phase. if an attacker suspects that a given parameter on a web page may be subject to a command injection attack (xss, sql, command, ssti, LFI, RFI, etc) then he can use this script to greatly speed up the testing phase. 
This tool has been integrated into siteSniper.
[siteSniper](https://github.com/dokDork/SiteSniper)


  
## Example Usage
CommandInjectionShield has been integrated in siteSniper so to execute it you need to execute siteSniper:
 ```
./siteSniper.sh eth0 https://www.example.com
 ``` 
<img src="https://github.com/dokDork/CommandInjectionShield/raw/main/images/01.png">

Then you need to select PHASE "5. WEB APP AUTHN BYPASS: brute force, command injection, webDAV, etc" 
<img src="https://github.com/dokDork/CommandInjectionShield/raw/main/images/02.png">

Then select SUB-PHASE "3 WEB Command Injection"
**(CTRL + b) w**  
<img src="https://github.com/dokDork/CommandInjectionShield/raw/main/images/03.png">

Tool will create some tmux session
<img src="https://github.com/dokDork/CommandInjectionShield/raw/main/images/04.png">
In the first line, the 3 main listeners are prepared: a listener for ICMP packets, a listener for SMB requests and a listener for HTTP requests. In the second line, two wfuzz calls are prepared, one for the GET calls and one for the POST calls. Data must be changed based on the parameter to be tested and then the program must be executed by pressing ENTER.
  
## Command-line parameters
Please refer to siteSniper
  
## How to install it on Kali Linux (or Debian distribution)
Please refer to siteSniper

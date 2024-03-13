# SiteSniper
[![License](https://img.shields.io/badge/license-MIT-_red.svg)](https://opensource.org/licenses/MIT)  
<img src="https://github.com/dokDork/CommandInjectionShield/raw/main/images/siteSniper.png" width="250" height="250">  
  
## Description
**CommandInjectionScript** is a script created to automate a specific penetration test phase: the command injection phase. if an attacker suspects that a given parameter on a web page may be subject to a command injection attack (xss, sql, command, ssti, LFI, RFI, etc) then he can use this script to greatly speed up the testing phase. 

  
## Example Usage
 ```
./siteSniper.sh eth0 https://www.example.com
 ``` 


  
## Command-line parameters
```
./siteSniper.sh <interface> <target url>
```

| Parameter | Description                          | Example       |
|-----------|--------------------------------------|---------------|
| `interface`      | network interface through which the target is reached | `eth0`, `wlan0`, `tun0`, ... |
| `target url`      | Target URL you need to test          | `http://www.example.com`          |

  
## How to install it on Kali Linux (or Debian distribution)
It's very simple  
```
cd /opt
```
```  
sudo git clone https://github.com/dokDork/red-team-penetration-test-script.git
```

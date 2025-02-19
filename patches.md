
# Services
This is a list of running services/patches for iOS 6 (some support iOS 5, but all services here support iOS 6). If I have forgotten a service, please DM me on Discord.

***

### Weather, Maps, Google Earth
- Install the WeatherX tweak from [cydia.bag-xml.com](https://cydia.bag-xml.com).
- Install the MapsX tweak from [cydia.bag-xml.com](https://cydia.bag-xml.com) (*location only, use Google Maps for navigation*).
- Install the EarthX tweak from [cydia.bag-xml.com](https://cydia.bag-xml.com)

***

### GameCenter
1. You will need to get the Certificates: "DigiCert Global Root CA G2" and "DigiCert Global Root CA G3" from [https://tlsroot.litten.ca/](https://tlsroot.litten.ca)

2. Next you need to install the app called iFile, navigate to the directory: "`/var/mobile/Library/Preferences`"

3. and look for anything folder that has anything to do with "`purplebuddy`", "`gamecenter`", and "`gamed`".

4. delete the files or move them after, next go to the directory: "`/var/mobile/Library/Caches`" and delete "`purplebuddy`"

5. after you deleted/moved those files, you need to either reboot or respring, then go through the setup screen like normal.

6. once you get to the Apple ID screen, make sure you sign in correctly since you have the Certificates.

(From `fifiisntawesum` in bag.xml's Discord server.)

[Patch for iOS 7](https://fifiisawesum.github.io/gamecenter7.html), [Original fix](https://fifiisawesum.github.io/gamecenter.html)

***

### Vine (Untitled Vine Revival)
Install the Vine app from [purplestore.a1429.lol/storefront](https://purplestore.a1429.lol/storefront). This is NOT the same as bag.xml's planned VineX, as VineX is a read-only archive while UVR is a new social platform that functions similar to Vine, like RetroGram by Savefade. You will need to make an account at [uvr.a1429.lol](https://uvr.a1429.lol).

***

### RetroGram
Grab the IPA from [rgdownload.sfproj.xyz/iOS](https://rgdownload.sfproj.xyz/iOS/). This is *not* an Instagram patcher, but rather a new social platform. 

***

### Twitter/Bluesky
This recreates Twitter API V1 good enough for the twitter clients to work.

API URL: https://twitterbridge.loganserver.net/  
Test/Beta API URL: https://testtwitterbridge.loganserver.net/  
(this does also work with android and other platforms than just iOS, most commonly requires patches, there's a patched android for test in there)

Primary IPA: [https://loganserver.net/twitters/ios/official/Twitter%204.1.3%20Unpatched.ipa](https://loganserver.net/twitters/ios/official/Twitter%204.1.3%20Unpatched.ipa)  
(tested on ios 4-6 so far)  
Other twitter versions can be found here: [https://loganserver.net/twitters/](https://loganserver.net/twitters)   
Source code can be found here: [https://github.com/Preloading/TwitterAPIBridge](https://github.com/Preloading/TwitterAPIBridge)  

Instructions:

1. Install the IPA of your choosing
2. Create a bluesky app password (assuming you have a bluesky account),menu > settings > privacy and security > app passwords. You will want to enable DMs for future DM compatibility.
3. Open the Twitter app
4. Click the login button
5. Click the cog button
6. Put `https://twitterbridge.loganserver.net` for both urls (you can make it http if on ios 3)
7. Type in your bluesky handle for the username, and your bluesky app password as the password
8. Login
9. Hopefully success

enjoy ❤️!

###### if you find this useful, please add a ⭐, https://github.com/Preloading/TwitterAPIBridge

(taken from bag.xml's Discord server)

***

### Telegram
Install the app from [legacyprojects.ru/telegram](https://legacyprojects.ru/telegram/). You will need a valid Telegram account from the official website before use.

***

### Discord
Install the app from [bag-xml.com/projects/discord-classic/](https://bag-xml.com/projects/discord-classic/). You will need your [Discord token](https://gist.github.com/MarvNC/e601f3603df22f36ebd3102c501116c6) to use.

***

### Facebook
(Instructions from [here](https://www.placek.site/other/how-to-fix-facebook-on-ios-6).)
1. Download Facebook 11 from [here](http://leovza.fr/ios/ipa/fb11.ipa).
2. Enable 2FA on your Facebook account.
3. Log in
4. Click `Open in Safari`
5. Put in your 2FA code (to be fair you can completly ignore it, and look at the notifications on your main phone. If you got a Facebook notification with a Warning sign, then click "Yes" If you've got the option.)
6. The browser should refresh on your older phone and successfully login into your account.  

This is a little buggy at the moment, and does not work on all devices.

***

### Tumblr
Install the Tumblr app version 3.4.3 from Veteris, then install Tumblere from [cydia.bag-xml.com](https://cydia.bag-xml.com).

***

### Spotify

Install the IPA from [here](https://github.com/Iemand005/FoxMusic/tags), and pair it with your Spotify account. It is a bit buggy, but the developer is starting to develop the project again.

***

### Reddit
Install the patched IPA from [here](https://mtmdev.org/webapp/applist.html) (top one), and install AB Media Fixer from [cydia.bag-xml.com](https://cydia.bag-xml.com) for better browsing experience.

***

### YouTube

Install the YouTube app version 1.1.0 or 2.0.0 [here](https://tuberepair.bag-xml.com), and install the tweak TubeRepair from [cydia.bag-xml.com](https://cydia.bag-xml.com).

***

### Google Translate

Download the [ReTranslate](https://github.com/Preloading/Retranslate/releases) tweak.

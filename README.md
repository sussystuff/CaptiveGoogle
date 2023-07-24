# CaptiveGoogle

"Captive Google" runs each of my families and some friends accounts (regardless of the device type) through a Google API. The splash page says Google Workspace but I suspect it’s not actually Workspace as they are subscription based and I only have a Google One subscription.

By leveraging a currently active exploit on macOS, iOS, ChromeOS and Android, the RATNinjas (as I call them) run the computer or device in developer mode, thereby effectively controlling all aspects of the device. 

This is a collection of evidence (although they are able to change and remove files and my Github login is running through an API as well, so who knows what wild things the RATNinjas may get up to). 

On my new 2023 Lenovo Chromebook, it didn’t take for the RATNinjas to comprise it. Using a (still) existing exploit, they modified the system to run crostini and effectively turned it into a mobile Android device (see images). Therefore, I am unable to run apps at full size (except Chrome the browser). The javascript file captiveGoogle.js (among others) contained information specific to my Google account(s). The presence of .test files references and suggests it is also collecting data from the session.
https://developer.android.com/kotlin/flow/test. Chromebook recovered scripts show active Field Trials in use.

I have tried to reach out to Google, but without a fully reverse engineered example including the specific entry point they are not interested. I have also attempted to reach out to threat hunters but have received no reply, it is possible thought that the RATNinjas are tampering with those communications. They impersonated Motorola through a fake "pre-installed" customer service app which was confirmed by @Moto on Twitter. 

So, the saga continues for myself and many others - at the mercy of our stealthy developer captors…

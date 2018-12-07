# fork from
fork from [https://github.com/floatinghotpot/cordova-facebook-audnet-sdk](https://github.com/floatinghotpot/cordova-facebook-audnet-sdk)

# how to use
*** modify ./platforms/ios/cordova/lib/Podfile.js 100 行 8.0 改为 9.0. for facebook 5.1.0 sdk***

`cordova plugin add https://github.com/floatinghotpot/cordova-facebook-audnet-sdk`
 
 
Or, use it as dependency of another plugin by reference in plugin.xml:
```xml
<dependency id="cordova-facebook-audnet-sdk" url="https://github.com/mingz2013/cordova-facebook-audnet-sdk"/>
```

---
---

# Old Readme

# Facebook AudienceNetwork SDK for Cordova

This cordova plugin add the Facebook SDK to cordova project.

Usually it's used as dependency of other plugins.

# How to Use

You can use it as dependency of another plugin by reference in plugin.xml:
```xml
<dependency id="cordova-facebook-audnet-sdk"/>
```

Or, you can also add it manually with Cordova CLI:
```bash
cordova plugin add cordova-facebook-audnet-sdk
```

# How to Update

Download the SDK from Facebook official site, unzip, replace the framework and jar.

https://developers.facebook.com/docs/ios/downloads

https://developers.facebook.com/docs/android/downloads


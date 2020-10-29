## Packages to remove from the Samsung Galaxy S7

All of these are packages I've removed safely from my own Galaxy S7 but everything is done at your own risk. If you're not comfortable or you don't know what something does for sure, **don't remove it**.

First up make sure you're in the ```ADB shell``` then remove pre-installed packages with the commands below. Either copy and paste all or pick and choose as you see fit.

I don't use Google Maps either but if you do, then don't copy that part. Otherwise this essentially just removes a lot of stuff you may not use or can be easily replicated with better apps. Likewise any apps or services you think you might want.

Let's start with an old favourite.

```
    #FACEBOOK JUNK
    pm uninstall -k --user 0 com.facebook.appmanager
    pm uninstall -k --user 0 com.facebook.system
    pm uninstall -k --user 0 com.facebook.services
    pm uninstall -k --user 0 com.facebook.katana
```



```
    pm uninstall -k --user 0 com.google.android.apps.maps
    pm uninstall -k --user 0 com.samsung.android.themestore
    pm uninstall -k --user 0 com.samsung.svoice.sync
    pm uninstall -k --user 0 com.samsung.android.calendar
    pm uninstall -k --user 0 com.samsung.android.email.provider
    pm uninstall -k --user 0 com.microsoft.office.excel
    pm uninstall -k --user 0 com.samsung.android.game.gamehome
    pm uninstall -k --user 0 com.microsoft.skydrive
    pm uninstall -k --user 0 com.samsung.android.messaging
    pm uninstall -k --user 0 com.samsung.android.app.memo
    pm uninstall -k --user 0 com.google.android.music
    pm uninstall -k --user 0 com.samsung.android.game.gametools
    pm uninstall -k --user 0 com.google.android.apps.docs
    pm uninstall -k --user 0 com.microsoft.office.word
    pm uninstall -k --user 0 com.microsoft.office.powerpoint
    pm uninstall -k --user 0 com.samsung.android.scloud
    pm uninstall -k --user 0 com.enhance.gameservice
```

This is only the very tip of a potentially large iceberg but just to get the project rolling I pulled out the most obvious stuff. This list will no doubts get much larger.

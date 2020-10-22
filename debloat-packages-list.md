## Packages to remove from the Samsung Galaxy S7

All of these are packages I've removed safely from my own Galaxy S7 but everything is done at your own risk. If you're not comfortable or you don't know what something does for sure, **don't remove it**.

First up make sure you're in the ```ADB shell``` then remove pre-installed packages with the commands below. Either copy and paste all or pick and choose as you see fit.

I don't use Google Maps either but if you do, then don't copy that part. Otherwise this essentially just removes a lot of stuff you may not use or can be easily replicated with better apps.

Oh, and Facebook stuff. Because you can uninstall the Facebook app from the phone but the services stuff behind remains.

```
    pm uninstall -k --user 0 com.google.android.apps.nbu.files
    pm uninstall -k --user 0 com.google.android.apps.maps
    pm uninstall -k --user 0
    pm uninstall -k --user 0
    pm uninstall -k --user 0
    pm uninstall -k --user 0
    pm uninstall -k --user 0
    pm uninstall -k --user 0
    pm uninstall -k --user 0
    pm uninstall -k --user 0
    pm uninstall -k --user 0
    pm uninstall -k --user 0
    pm uninstall -k --user 0
    pm uninstall -k --user 0
    pm uninstall -k --user 0
    pm uninstall -k --user 0
    pm uninstall -k --user 0
    pm uninstall -k --user 0
    pm uninstall -k --user 0 
```

```
    #FACEBOOK JUNK
    pm uninstall -k --user 0 com.facebook.appmanager
    pm uninstall -k --user 0 com.facebook.system
    pm uninstall -k --user 0 com.facebook.services
```

If I discover anything has broken or more stuff I can remove I'll be updating this list accordingly.

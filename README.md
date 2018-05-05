
# ro.build.type to user

## Description
Sets ro.build.type to "user".

Some Custom ROMs (namely LineageOS) set ro.build.type to "userdebug" to access specific features or for compatibility reasons. Not every device needs this, so ro.build.type can be set to "user" to disable unnecessary debugging, but for Custom ROMs which provide updates you'd have to do this every time after flashing an update.

This module takes the work off you and also does this without modifying the system partition.
## Changelog
v1 - Initial Release
## Instructions
Simply either download it off the online repo or download the GitHub repo linked below and add it in the Magisk App afterwards.
## Links
[Module on GitHub](https://github.com/pongo1231/magisk-buildtype-to-user)

[Latest stable Magisk](http://www.tiny.cc/latestmagisk)

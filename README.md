# xash-android10-coop
this version of xash3d are based on
https://github.com/FWGS/xash3d-deploy/tree/travis-master
with small modification on AndroidManifest.xml
to allow screen recorders apps to record internal audio of this game in android 10.0 and higher version
all credits to fwgs team
https://github.com/FWGS

pre-signed apk found here
https://github.com/abasgames/xash-android10-coop/files/5394213/xash3d.coop.with.internal.audio.support.android.10.and.up.zip

requirements for compiler

1-a pc and an android phone atleast runs android 10.0

2-7zip https://www.7-zip.org/

3-apktool get it from https://ibotpeaches.github.io/Apktool/install/

4-in order to install our compiled apk we well need to sign the apk first i well uses apk-signer from google play 

you can found alot of tools to sign your apk in internet

time for compiling

1-clone this repo by git clone https://github.com/abasgames/xash-android10-coop

2-right click on xash3d.zip and extract to "xash3d/" with 7zip

3-press shift + right mouse click inside the project folder not inside xash3d

then click open command window here

4-type apktool d xash3d it well takes some seconds to finish. after that

5-go to xash3d folder then dist and you well find the apk there

6-sign it with any tool you like and install it in your device. done


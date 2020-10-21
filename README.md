# Cracked-Launcher
This is only for use on the Raspberry Pi 4.  
The username can be anything you want.  
The password is raspberry.  
This will alow you to play Minecraft in offline mode for free and be able to join servers that have the option cracked enabled
## To install:
```
sudo mv /usr/share/minecraftjava/launcher.jar /usr/share/minecraftjava/oldlauncher.jar
sudo wget https://github.com/boomerangos/Cracked-Launcher/blob/master/crackedlauncherVer1.1.jar?raw=true -O /usr/share/minecraftjava/launcher.jar
```
## To Launch Minecraft you need to add code to the JVM Section
## Minecraft Java (armhf) (32bit)
## Minecraft 1.12 and Older 
```
-Dorg.lwjgl.librarypath=/home/pi/lwjgl2arm32 
```
## Minecraft 1.13 and Newer
```
-Dorg.lwjgl.librarypath=/home/pi/lwjgl3arm32
```
## Minecraft Java (arm64) (64bit)
## Change Path For Java
```
/opt/jdk/jdk1.8.0_251/bin/java
```
## Minecraft All Versions
```
-Dorg.lwjgl.librarypath=/home/pi/lwjgl3arm64
```
## Download Optifine 
```
https://optifine.net/downloads
```

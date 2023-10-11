# Frida-Scripts
Useful Frida Scripts

Commands:

Install Frida - https://infosecwriteups.com/hail-frida-the-universal-ssl-pinning-bypass-for-android-e9e1d733d29

Root Detection/ Emulator Bypass:
frida -l root-killer.js -U -f com.example.app

Setup of Platform Tools:
Download Platform Tools - https://developer.android.com/tools/releases/platform-tools

## Static Checks:
adb devices /n
adb shell 
su
cd /data/data/com.example.com

1. cd SharedPrefs (To check issues for Shared Preferences)
2. cd Databases (To check issues for DB)
3. logcat | grep 'access_token'
4. logcat | grep 'email@domain.com'
5. logcat | grep 'password'

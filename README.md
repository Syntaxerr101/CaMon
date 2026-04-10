# <div > **CaMon**  </div>

![Downloads](https://img.shields.io/github/downloads/Syntaxerr101/CaMon/total) [![Telegram Channel](https://img.shields.io/badge/Telegram-Channel-blue.svg?logo=telegram)](https://t.me/camm0n) ![Latest Release](https://img.shields.io/github/v/release/Syntaxerr101/CaMon)  


## Camera usage monitor 

Privacy tool that detects and logs which apps use your camera

Why i built this tool?
While checking my device, I discovered that com.google.android.gms (Google Play Services) was accessing my camera every 5 seconds - with permissions enabled by default. No warning. No transparency.
This tool lets you see exactly who's using your camera and when.

## Screenshots  

<p align="center">
  <img src="https://github.com/Syntaxerr101/CaMon/blob/main/2.png" width="46%" />
  <img src="https://github.com/Syntaxerr101/CaMon/blob/main/1.png" width="46%" />  
</p>  
<p align="center">

 
## Features

- Real-time camera usage detection
- Logs which app accessed the camera and when
- Shows access frequency per app
- Search & filter history
- Export logs to file

## Permissions

- Camera: Detect camera state changes
- Usage: access Identify which app is using the camera
- Notification: Show monitoring service is active

## Important Notes

- Camera & Usage access permissions are used ONLY for monitoring camera activity. No internet permission is included - your data never leaves your device.
- Privacy first - This tool was built for my own privacy. I expect you to use it for the same reason.
- Known limitation - CamMon runs without root access and cannot monitor at kernel level. It does its best to detect camera usage within standard user permissions. Some events may occasionally be missed

Quick Start:
1. Install the app
2. Grant Camera permission
3. Enable Usage access (Settings → Apps → Special access → Usage access)
4. Toggle monitor ON


Made by **Simo** with the help of Ai.

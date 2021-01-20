<h1 align="center">
  <br>
  <a href="https://github.com/shansekai/Sansekai-BOT"><img src="https://raw.githubusercontent.com/shansekai/yusril-grabbed-result/main/weebs/123668954_681176676120525_7298275727742867146_n.jpg"></a>
  <br>
  Sansekai BOT Whatsapp
 <br>
  </h1>

## Getting Started

This project require NodeJS v12.

### Install
Install Ffmpeg & Clone this project

### FFMPEG & LIBWEB
- [DOWNLOAD FFMPEG](https://github.com/BtbN/FFmpeg-Builds/releases/) or [Download FFMPEG2](https://www.wikihow.com/Install-FFmpeg-on-Windows)
- [DOWNLOAD LIBWEB](https://developers.google.com/speed/webp/download)

```bash
> git clone https://github.com/shansekai/Sansekai-BOT
> cd imageToSticker
```

Install the dependencies:

```bash
> npm install
> npm install -g pm2
```

### Usage
1. run the Whatsapp bot

```bash
> npm start
```

2. run the Whatsapp bot with pm2
```bash
> pm2 start run.js
> pm2 monit
```
3. stop the Whatsapp bot if use pm2

for npm :
```bash
> ctrl + c
```
for pm2 :
```bash
> pm2 stop run.js
```

## PATH
> C:\ffmpeg\bin;C:\Users\Administrator\AppData\Roaming\npm;C:\libweb\bin

after running it you need to scan the qr

## Troubleshooting
Make sure all the necessary dependencies are installed: https://github.com/puppeteer/puppeteer/blob/main/docs/troubleshooting.md

Fix Stuck on linux, install google chrome stable: 
```bash
> wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
> sudo apt install ./google-chrome-stable_current_amd64.deb
```
If you having problem when installing the modules (most likely when installing Quick.db), please [READ THIS](https://stackoverflow.com/questions/55152761/npm-wont-install-quick-db-returns-these-errors).
Also, if error still occurs and don't know what to do please make an issue on [this repo](https://github.com/JoshuaWise/better-sqlite3/), thank you.


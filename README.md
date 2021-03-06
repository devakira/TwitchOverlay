# [TwitchOverlay](https://overlay.twitchbot.io)

[![](https://img.shields.io/github/release/devakira/twitchoverlay.svg?colorB=g&style=flat-square)](https://github.com/devakira/TwitchOverlay/releases/latest)
[![](https://img.shields.io/github/downloads/devakira/twitchoverlay/total.svg?colorB=blue&style=flat-square)](https://github.com/devakira/TwitchOverlay/releases/latest)

A custom, minimal Twitch client and stream player made with Electron.

![image](https://cdn.discordapp.com/attachments/376375897109954560/536553108747321354/unknown.png)

## Requirements

 - Windows (64-bit)

## Installing

Go to the [releases](https://github.com/devakira/TwitchOverlay/releases) page and download 'TwitchOverlay.exe' to use the production build.

### Development Build

#### Dev requirements

- Node 10 or above
- Electron 4
- electron-builder

```sh
git clone https://github.com/devakira/TwitchOverlay
cd TwitchOverlay
npm install
electron .
```

## Logging in

As of Sept. 17, 2013, Twitch now requires that you log into IRC using an OAuth token instead of your plaintext password or hash for additional security. To generate an oAuth token, go to https://twitchapps.com/tmi/, click `Connect with Twitch`, and copy the text in the box.

## Building

```sh
npm install
./node_modules/.bin/build --windows portable
```

This will generate an executable at `./dist/TwitchOverlay (version).exe`.

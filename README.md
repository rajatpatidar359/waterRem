# Water Me 🪴

> A simple, open and privacy friendly plant watering reminder for Android.
  
  [![Build APK](https://github.com/abertschi/water-me/actions/workflows/build.yml/badge.svg)](https://github.com/abertschi/water-me/actions/workflows/build.yml)
   ![Made with Flutter](https://img.shields.io/badge/Made%20with-Flutter-1f425f.svg)
   [![version](https://img.shields.io/github/v/tag/abertschi/water-me?label=latest%20version)](https://img.shields.io/github/v/tag/abertschi/water-me?label=latest%20version)
<p align="left">
    <img src="./assets/preview2.png" alt="preview" width="800"/>
</p>

_Water me_ is a mobile application written in Flutter to  remind you to water your plants. No ads, no account, no sign-up, no tracking.

### Features and Components
- Add plants with watering frequency, name and picture
- No remote entity, local-only application
- Flutter, currently support for Android
- Camera access
- Local Notifications
- Workmanager with periodic task
- Backup and Restore to json format
- Provider package for MVC separation
  
### Install
_Water Me_ is available on the [F-droid store](https://f-droid.org/packages/ch.abertschi.waterme.water_me) [(Metadata)](https://gitlab.com/fdroid/fdroiddata/-/blob/master/metadata/ch.abertschi.waterme.water_me.yml).

[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png"
    alt="Get it on F-Droid"
    height="80">](https://f-droid.org/packages/ch.abertschi.waterme.water_me)

Alternatively, download snapshots from the [continuous integration action](https://github.com/abertschi/water-me/actions/workflows/build.yml) (requires a Github account, be aware that Github zips the apk on download, so unzip first).


### Changelog
See [./CHANGELOG](./CHANGELOG) for a list of recent features.

### Need Help?
See [troubleshooting guide](./qna.md) for a list of common questions.

### Build
This is a flutter based Android application. Ensure to have Android-Studio and flutter-sdk installed.
```
flutter pub get
flutter build apk
```

The entire build process in captured in [scripts/build.sh](https://github.com/abertschi/water-me/blob/master/scripts/build.sh).
 
### Feature and Contribution Ideas
Pull requests are welcome :heart:.

- [x] A better logo :) [#4](https://github.com/abertschi/water-me/issues/4)
- [ ] Enable 'web' target to build a web app for ios/ web (needs a backend for notifications).
- [ ] Integrate firebase/ self hosted backend to enable a group mode to sync plant state within a group of users
- [ ] Add a 'note' field to a plant
- [ ] Show watering history in plant detail screen.
- [ ] Allow assignment of plants into groups, e.g. living room, office

And [more ideas](https://github.com/abertschi/water-me/issues).

### License
GPL v3

### About
Built with <3   
by Andrin Bertschi  
https://abertschi.ch
#   w a t e r R e m  
 #   w a t e r R e m  
 #   w a t e r  
 #   w a t e r R e m  
 
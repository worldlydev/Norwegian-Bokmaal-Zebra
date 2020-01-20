# WorldlyDev’s Zebra Fork

This fork is now archived as it has been merged into the original repository. It added Norwegian Bokmål and Norwegian Nynorsk localizations.
- https://github.com/wstyres/Zebra/pull/410
- https://github.com/wstyres/Zebra/pull/412
- https://github.com/wstyres/Zebra/pull/464
- https://github.com/wstyres/Zebra/pull/486

The localizations are hosted on Crowdin and can be editited here:
https://crowdin.com/project/zebra

---

# Zebra [![Build Status](https://travis-ci.org/wstyres/Zebra.svg?branch=master)](https://travis-ci.org/wstyres/Zebra)
Zebra (neé AUPM) is a Package Manager for jailbroken iOS devices. It is built to support iOS 9 up to iOS 12 and for iPhones and iPads alike.

## Translations

Zebra supports localization but help is needed in order to translate Zebra!

If you are familiar with a language that is not currently supported by Zebra (you can check out a list of curently supported languages [here](https://github.com/wstyres/Zebra/blob/master/translations.md)), you can help us out by translating Zebra into your language. There are two ways to do this:

1. If you do not know how to use Xcode or are not able to use Xcode, you can download Zebra's strings from [here](https://getzbra.com/localization/Localizable.strings), and translate them one-by-one. The English strings are on the left side while the strings that needed to be translated are placed on the right side. Once you are done, you can [file an issue](https://github.com/wstyres/Zebra/issues/new?assignees=&labels=localization&template=localization-support.md&title=%5BLocalize%5D) with a link to your translated Localizable.strings and we will review it for inclusion in Zebra.

2. If you are comfortable using Xcode, you can add a new language to the Zebra project, translate all of the strings (located in the Base.lproj folder), and then submit a [Pull Request](https://github.com/wstyres/Zebra/compare) with your translated .strings file and we will review it for inclusion in Zebra.

If there is a language that has an inaccurate translation that is already supported by Zebra, you can [locate the .strings file](https://github.com/wstyres/Zebra/tree/master/Zebra/Base.lproj) and edit it directly from GitHub, create a new Pull Request, an it will be reviewed for inclusion in Zebra.

New strings may be added in future Zebra versions from time to time so it is important to keep a look out for modified strings!

## Bug Reports
The best way to report a bug with Zebra is to open an issue [here](https://github.com/wstyres/Zebra/issues/new?assignees=wstyres&labels=bug&template=bug_report.md&title=).

Fill out the required fields as best that you can in order to have a better chance at getting your issue fixed.

I may require some additional information in order to isolate the issue in question and may ask for your response. Your help is appreciated.

You must create a GitHub account to create an issue. If you do not have one, it is free to create one by signing up or you can email me your bug report from within Zebra.

## Feature Requests
Feature request are welcome as well and are also tracked through GitHub issues [here](https://github.com/wstyres/Zebra/issues/new?assignees=&labels=enhancement&template=feature_request.md&title=).

Fill out the required fields to the best of your ability (mockups, screenshots, descriptions, etc.).

You must create a GitHub account to create an issue. If you do not have one, it is free to create one by signing up or you can email me your feature request from within Zebra.

## Pull Requests
Pull requests to fix bugs, add new features, and fix awful code (I'm sure there is a lot) are also very welcome and I'm happy to work with you in order to get your PR into Zebra.

## Installation
#### From an APT Repo
Zebra is available from Zebra's APT repo for iOS located [here](https://getzbra.com/repo).

This source can be added to any package manager on your iPhone or iPad and it is included by default with Zebra to provide future updates.

Zebra also has a beta repository that contains builds for beta testers to try out new features and report potential problems you can add Zebra's beta APT repo for iOS located [here](https://getzbra.com/beta).

#### Pre-compiled debs
Pre-compiled debs are available via GitHub [releases](https://github.com/wstyres/Zebra/releases), if that is your fancy.

#### Using Xcode & theos
If you want to compile Zebra yourself, you can use the following steps. A computer running macOS is _required_ and must have Xcode installed.

1. Clone this repository using `git clone --recursive https://github.com/wstyres/Zebra.git`
2. `cd` into the `Zebra` folder
3. run `make do`
   1. If you don't have `theos` already installed on your computer, follow the steps located [here](https://github.com/theos/theos/wiki/Installation).
4. Done!

<p align="center">
<img height="300" width="300" src="https://raw.githubusercontent.com/lbrndnr/nuage-macos/master/Nuage/Assets.xcassets/AppIcon.appiconset/AppIcon512@2x.png" />
</p>

<h1 align="center">Nuage</h1>
<p align="center">A native SoundCloud app for macOS, written in SwiftUI</p>

---

[![Twitter: @lbrndnr](https://img.shields.io/badge/contact-@lbrndnr-blue.svg?style=flat)](https://twitter.com/lbrndnr)
[![License](http://img.shields.io/badge/license-MIT-green.svg?style=flat)](https://github.com/lbrndnr/nuage-macos/blob/master/LICENSE)

## About
Nuage is an independent and open-source project to build a native SoundCloud client for macOS using SwiftUI. Its overall goal is to make listening to tracks on SoundCloud more enjoyable by providing a light-weight and beautiful interface. As of now, the app is still very much in development, lots of features are still missing and the UI needs a lot of work too. So if you want to learn a little bit of SwiftUI or if you have a suggestion regarding the user experience, feel free to open an issue or a merge request.

<img alt="Nuage Main View" src="https://github.com/lbrndnr/nuage-macos/assets/762049/919de8d7-8f29-4176-a701-33a52c21f74d">

Note that Nuage is not affiliated in any way to SoundCloud. Nuage uses private APIs which I have not been granted access to, so functionality may break in the future.

## Installation

You can install Nuage using brew:
```console
$ brew install --cask nuage
```
or by downloading the latest version right [here](https://github.com/lbrndnr/nuage-macos/releases). Note that Nuage is still in heavy development and on top of that written in SwiftUI, a very young framework. If you encounter a bug or miss a feature, don't hesitate to open a pull request.

## Dependencies

Nuage uses [StackNavigationView](https://github.com/lbrndnr/StackNavigationView) to push views onto the view hierarchy (which is not currently possible with SwiftUI 2) and [SoundCloud](https://github.com/lbrndnr/soundcloud) to access SoundCloud's private API.

## Code & Design
Developed by [Laurin Brandner](https://twitter.com/lbrndnr), icon designed by [Yannick Lung](https://twitter.com/yannicklu).

## License
Nuage is licensed under the [MIT License](http://opensource.org/licenses/mit-license.php).

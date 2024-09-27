ZoomableSwiftImageView
======================
A customizable and lightweight SwiftUI image viewer with smooth zooming, panning and double-tap-to-zoom functionality.

[<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/IODevBlue/ZoomableSwiftImageView?label=Current Version&color=2CCCE4&style=for-the-badge&labelColor=0109B6">](https://github.com/IODevBlue/ZoomableSwiftImageView/releases) <img alt="Repository Size" src="https://img.shields.io/github/repo-size/IODevBlue/ZoomableSwiftImageView?color=2CCCE4&style=for-the-badge&labelColor=0109B6"> [<img alt="License" src="https://img.shields.io/github/license/IODevBlue/ZoomableSwiftImageView?color=2CCCE4&style=for-the-badge&labelColor=0109B6">](http://www.apache.org/licenses/LICENSE-2.0) [<img alt="GitHub Repository stars" src="https://img.shields.io/github/stars/IODevBlue/ZoomableSwiftImageView?color=2CCCE4&style=for-the-badge&labelColor=0109B6">](https://github.com/IODevBlue/ZoomableSwiftImageView/stargazers)
<img alt="GitHub watchers" src="https://img.shields.io/github/watchers/IODevBlue/ZoomableSwiftImageView?label=Repository Watchers&color=2CCCE4&style=for-the-badge&labelColor=0109B6">


Table of content
----------------
- [Requirements](https://github.com/IODevBlue/ZoomableSwiftImageView/tree/main#requirements)
- [Uses](https://github.com/IODevBlue/ZoomableSwiftImageView/tree/main#uses)
- [Features](https://github.com/IODevBlue/ZoomableSwiftImageView/tree/main#features)
- [Installation](https://github.com/IODevBlue/ZoomableSwiftImageView/tree/main#installation)
- [Usage](https://github.com/IODevBlue/ZoomableSwiftImageView/tree/main#usage)
- [Applications using ZoomableSwiftImageView](https://github.com/IODevBlue/ZoomableSwiftImageView/tree/main#applications-using-ZoomableSwiftImageView)
- [Contributions](https://github.com/IODevBlue/ZoomableSwiftImageView/tree/main#contributions)
- [Changelog](https://github.com/IODevBlue/ZoomableSwiftImageView/tree/main#changelog)
- [License](https://github.com/IODevBlue/ZoomableSwiftImageView/tree/main#license)

Requirements
------------
- iOS 13.0+
- macOS 11.0+
- Xcode 11+


Uses
----
Image Galleries: Display images where users can zoom in and out on images for a detailed view.


Features
--------
- <details>
	<summary>Zooming Capabilities</summary>
	<p>Pinch to zoom in and out of the displayed image allowing for detailed inspection of the image content.</p>
	<p align="center"><img src="https://github.com/IODevBlue/sample-previews/blob/main/api/ios/zoomable-swift-imageview/zooming.gif" alt="Zooming"></p>
</details>


- <details>
	<summary>Double Tap to Zoom</summary>
	<p align="center"><img src="https://github.com/IODevBlue/sample-previews/blob/main/api/ios/zoomable-swift-imageview/double-tap-to-zoom.gif" alt="Double Tap to Zoom"></p>
</details>

- <details>
	<summary>Panning Functionality with Snapback</summary>
	<p>Pinch to zoom in and out of the displayed image allowing for detailed inspection of the image content.</p>
	<p align="center"><img src="https://github.com/IODevBlue/sample-previews/blob/main/api/ios/zoomable-swift-imageview/panning-with-snapback.gif" alt="Panning with Snapback"></p>
</details>


Installation
------------
**Current Version: 1.0.0**

There are several ways to install this library.

1. Using Swift Package Manager (SPM):
- In Xcode, go to `File` > `Add Package Dependencies...`
- Enter the repository URL: https://github.com/IODevBlue/ZoomableSwiftImageView.git.
- Choose the version you want to install (e.g., 1.0.0).

2. CocoaPods:
- Add the following line to your Podfile:
```ruby
pod 'ZoomableSwiftImageView', '~> 1.0.0'
```
- Then run:
```bash
pod install
```

3. Carthage:
- Add the following line to your Cartfile:
```ruby
github "IODevBlue/ZoomableSwiftImageView" ~> 1.0.0
```
- Then run:
```bash
carthage update --platform iOS
```
- Follow the instructions to link the framework to your project.

4. Manually:
[Download](https://github.com/IODevBlue/ZoomableSwiftImageView/archive/refs/heads/main.zip) the project zip file.
- Navigate to the `Sources` folder and copy the `ZoomableSwiftImageView` subfolder into your Xcode project.
- Alternatively, `ZoomableSwiftImageView` is a single source file. You can just copy the `ZoomableSwiftImageView.swift` file to your Xcode project.

If you do make major or minor improvements to the source code, consider making a pull request or an issue to make a contribution.
Check the [Contributing](https://github.com/IODevBlue/ZoomableSwiftImageView/blob/development/CONTRIBUTING.md) for more information.



Usage
-----
Create an instance of `ZoomableSwiftImageView` by providing an `Image`:
```swift
import SwiftUI

struct ContentView: View {
    var body: some View {
        ZoomableSwiftImageView(image: Image("your_image_name"))
    }
}
```



Applications using ZoomableSwiftImageView
------------------------------------------
If your application uses ZoomableSwiftImageView and you'd love to showcase, send an <a href="mailto:iodevblue@gmail.com">email</a> containing:
- An app icon
- A link to download your application.
- A related Github repository.



Contributions
-------------
Contributors are welcome!

**NOTE:** This repository is split into two branches:
- [main](https://github.com/IODevBlue/ZoomableSwiftImageView/tree/main) branch
- [development](https://github.com/IODevBlue/ZoomableSwiftImageView/tree/development) branch

All developing implementations and proposed changes are pushed to the [development](https://github.com/IODevBlue/ZoomableSwiftImageView/tree/development) branch and finalized updates are pushed to the [main](https://github.com/IODevBlue/ZoomableSwiftImageView/tree/main) branch.


Check the [Contributing](https://github.com/IODevBlue/ZoomableSwiftImageView/blob/development/CONTRIBUTING.md) for more information.



Changelog
---------
* **1.0.0**
    * Initial release

More version history can be gotten from the [Change log](https://github.com/IODevBlue/ZoomableSwiftImageView/blob/main/CHANGELOG.md) file.



License
=======
```
    Copyright 2024 IO DevBlue

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
```


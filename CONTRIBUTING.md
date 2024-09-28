Contributing
============

<img alt="GitHub forks" src="https://img.shields.io/github/forks/IODevBlue/ZoomableSwiftImageView?label=Forks&color=2CCCE4&style=for-the-badge&labelColor=0109B6"> <img alt="Number of issues" src="https://img.shields.io/github/issues-raw/IODevBlue/ZoomableSwiftImageView?color=2CCCE4&style=for-the-badge&labelColor=0109B6"> <img alt="Closed issues" src="https://img.shields.io/github/issues-closed-raw/IODevBlue/ZoomableSwiftImageView?color=2CCCE4&style=for-the-badge&labelColor=0109B6">

<img alt="Number of pull requests" src="https://img.shields.io/github/issues-pr-raw/IODevBlue/ZoomableSwiftImageView?color=2CCCE4&style=for-the-badge&labelColor=0109B6"> <img alt="Closed pull requests" src="https://img.shields.io/github/issues-pr-closed-raw/IODevBlue/ZoomableSwiftImageView?color=2CCCE4&style=for-the-badge&labelColor=0109B6">

<img alt="GitHub contributors" src="https://img.shields.io/github/contributors/IODevBlue/ZoomableSwiftImageView?color=2CCCE4&style=for-the-badge&labelColor=0109B6">

<img alt="Last commit for development" src="https://img.shields.io/github/last-commit/IODevBlue/ZoomableSwiftImageView/development?color=2CCCE4&style=for-the-badge&labelColor=0109B6">

Current tasks to be completed
-----------------------------
- [ ] Callbacks for user dragging and magnification gestures.
- [ ] Expose API to set zoom in and zoom out limits.
- [ ] Expose API to set smoothness of the panning.
- [ ] Extension function `makeZoomable()` on an `Image` instance to make it zoomable.
- [ ] Initializer that takes in a `UIImage` instance.
- [ ] Rotation Gesture: Allow the image to be rotated with a two-finger gesture.
- [ ] Zoom level indicator.
- [ ] Tap-and-Hold Zoom: Allow tapping and holding the screen to zoom in, then release to zoom out.


- Have a new feature in mind?
- Want to make changes and improvements to documentations and code?
- Noticed an error?
- Found a bug?

Contributions are welcome and encouraged!!

Make a [fork](https://github.com/IODevBlue/ZoomableSwiftImageView/fork) of the repository and send a pull request.

Discussions about your code, logical decisions and proposed changes would be made before pushing to the [main](https://github.com/IODevBlue/ZoomableSwiftImageView/tree/main) repository branch.

Concerning Issues
-----------------
- Before creating an issue, please verify if a pre-existing and similar issue already exists. 
- If an issue is closed and problem persists, you can reopen that same issue or create an entirely new issue.
- Persistent bugs can be better illustrated using a unit/integrated test, demo project, JPG/JPEG file, GIF animation, stack traces and logs.

**NOTE:** 

When posting code blocks, logs or stack traces etc, please use Github flavoured markdown syntax to improve readability.

For Swift code blocks, it's preferable to use Swift comments with Swift-flavored syntax.

Concerning Code Style
---------------------
Consistent indentation plays an important role in readability and maintainability of code.
 
The indentation currently used in this project is as follows:
- For Swift:
```swift
func correctIndent() {
	doSomethingHere {
		let x = "some string var"
	}
}
```
Wrong indentation:
```swift
func inCorrectIndent() 
{
	doSomethingHere 
	{
		let x = "some string var"
	}
}
```


Please follow the correct indentation style.

Apple Samples Ported to Swift
============

Like a lot of other developers I'm trying to familiarize myself with Swift.

Towards that goal I'm porting some of the [Apple sample code](https://developer.apple.com/library/ios/navigation/#section=Resource%20Types&topic=Sample%20Code) to Swift.

In general, I'm doing the following to each project before I start changing the code:

* Convert to Objective-C ARC
* Convert to Modern Objective-C Syntax
* Update Deployment Targets to iOS 8.0
* Validate the project settings and let Xcode change them as it wants
* Add Default-568h@2x.png to allow for running on an iPhone 5

Then I start diving into it one file at a time.

I'll add notes and comments as I go along and discover stuff of note.

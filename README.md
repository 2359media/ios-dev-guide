# iOS Development Guide

This development guide outlines the standards and the best practices that are adopted by the iOS team at 2359 Media.

This is the first draft of the guide. We are eager for the feedback from our developers. Please feel free to create [issues](https://github.com/2359media/ios-dev-guide/issues) for any suggestions.

## Table of Contents

* [Objective-C Coding Style](#objective-c-coding-style)
* [Libraries](#libraries)
	* [CocoaPods](#cocoapods)
	* [Recommended Libraries](#recommended-libraries)
		* [Networking](#networking)
		* [JSON Parsing](#json-parsing)
		* [Urban Airship (Device Registration)](#urban-airship-device-registration)
		* [HUD](#hud)
		* [Reachability](#reachability)
		* [Pull-to-Refresh](#pull-to-refresh)
		* [Social Network](#social-network)
		* [UICollectionView on iOS 5.x](#uicollectionview-on-ios-5x)
		* [Attributed Label](#attributed-label)
		* [Sidebar Menu (Hamburger UI)](#sidebar-menu-hamburger-ui)
		* [UIView (Nib Loading and Geometry Shortcuts)](#uiview-nib-loading-and-geometry-shortcuts)
		* [Page Control](#page-control)
		* [UIAlertView and UIActionSheet (Block-based wrappers)](#uialertview-and-uiactionsheet-block-based-wrappers)
* [Xcode](#xcode)

## Objective-C Coding Style

Please refer to [2359media/objective-c-conventions](https://github.com/2359media/objective-c-conventions)

## Third-party Libraries

We often use 3rd-party libraries in iOS projects. 

### CocoaPods

[CocoaPods](http://cocoapods.org) should be used to manage libraries instead of copying library source files into the project.

* Library with *podspec* in [CocoaPods/Specs](https://github.com/CocoaPods/Specs)

		pod 'AFNetworking', '2.0.0-RC3'

* Library with *podspec* in the root of the repo

		pod 'AFNetworking', :git => 'https://github.com/AFNetworking/AFNetworking.git'

* Library without *podspec*

		pod 'JSONKit', :podspec => 'https://raw.github.com/gist/1346394/1d26570f68ca27377a27430c65841a0880395d72/JSONKit.podspec'

### Recommended Libraries

Here are a list of libraries that are widely used in our projects. Developers are recommended to choose the listed library for that particular feature. If, however, developers want to use a different library or experiment a new library. Please [create a new issue](https://github.com/2359media/ios-dev-guide/issues/new) to argue that why an alternate library is better. 

#### Networking

[AFNetworking](https://github.com/AFNetworking/AFNetworking) by Mattt Thompson

> A delightful iOS and OS X networking framework.
> http://afnetworking.com

AFNetworking 2.0 officially supports iOS 6+, Mac OS X 10.8+, and Xcode 5. If you'd like to use AFNetworking in a project targeting a base SDK of iOS 5, or Mac OS X 10.7, use the latest tagged 1.x release. For iOS 4.3 and Mac OS X 10.6 support, use the latest tagged 0.10.x release.

#### JSON Parsing

1. [NSJSONSerialization](https://developer.apple.com/library/ios/documentation/Foundation/Reference/NSJSONSerialization_Class/Reference/Reference.html) (iOS 5+)

2. [JSONKit](https://github.com/johnezang/JSONKit) by John Engelhart

> A Very High Performance Objective-C JSON Library

#### Urban Airship (Device Registration)

[AFUrbanAirshipClient](http://github.com/AFNetworking/AFUrbanAirshipClient) by Mattt Thompson

> An API Client for Registering and Unregistering Devices with Urban Airship.

#### HUD

[SVProgressHUD](https://github.com/samvermette/SVProgressHUD) by Sam Vermette

> A clean and lightweight progress HUD for your iOS app.  
> <http://samvermette.com/199>

#### Reachability

[Reachability](https://github.com/tonymillion/Reachability) by Tony Million

> ARC and GCD Compatible Reachability Class for iOS and MacOS. Drop in replacement for Apple Reachability.

#### Pull-to-Refresh

1. [UIRefreshControl](https://developer.apple.com/library/ios/documentation/uikit/reference/UIRefreshControl_class/Reference/Reference.html) (iOS 6+)

2. [SVPullToRefresh](https://github.com/samvermette/SVPullToRefresh) by Sam Vermette

> Give pull-to-refresh & infinite scrolling to any UIScrollView with 1 line of code.  
> <http://samvermette.com/314>

#### Social Network

1. [UIActivityViewController](https://developer.apple.com/library/ios/documentation/uikit/reference/UIActivityViewController_Class/Reference/Reference.html)

	Use system sharing sheet, so no custom UI is allowed. Use it whenever possible.

2. [Social.framework](https://developer.apple.com/library/ios/documentation/Social/Reference/Social_Framework/_index.html) (iOS 6+)

3. [Twitter.framework](https://developer.apple.com/library/ios/documentation/Twitter/Reference/TwitterFrameworkReference/_index.html) (Twitter only and iOS 5 only, deprecated in iOS 6)

4. [Facebook SDK for iOS](https://developers.facebook.com/docs/ios/) by Facebook

	Use it for everything related to Facebook, including Facebook login, Facebook sharing, user profile, friend list, etc.

#### UICollectionView on iOS 5.x

[PSTCollectionView](https://github.com/steipete/PSTCollectionView) by Peter Steinberger

> Open Source, 100% API compatible replacement of UICollectionView for iOS4.3+

#### Attributed Label

[TTTAttributedLabel](https://github.com/mattt/TTTAttributedLabel) by Mattt Thompson

> A drop-in replacement for UILabel that supports attributes, data detectors, links, and more

#### Sidebar Menu (Hamburger UI)

[MMDrawerController](https://github.com/mutualmobile/MMDrawerController) by Mutual Mobile

> A lightweight, easy to use, Side Drawer Navigation Controller

#### UIView (Nib loading and Geometry shortcuts)

[ViewUtils](https://github.com/nicklockwood/ViewUtils) by Nick Lockwood

> ViewUtils is a collection of category methods designed that extend UIView with all the handy little properties and functionality that you always wished were built-in to begin with.

#### Page Control

[DDPageControl](https://github.com/ddeville/DDPageControl) by Damien DeVille

> An easily customizable alternative to UIKit's UIPageControl

#### UIAlertView and UIActionSheet (Block-based wrappers)

[PSAlertView](https://github.com/steipete/PSAlertView) by Peter Steinberger

> Modern block-based wrappers for UIAlertView and UIActionSheet.

## Xcode

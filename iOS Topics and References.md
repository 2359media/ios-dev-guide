Objective-C & iOS
=================

1. Object-Oriented Programming:
-------------------------------

###Syntax:

- [Cheat sheet from Raywenderlich](http://cdn1.raywenderlich.com/downloads/RW-Objective-C-Cheatsheet-v-1-5.pdf)

- Conventions from [NYTimes](https://github.com/NYTimes/objective-c-style-guide), [Github](https://github.com/github/objective-c-conventions), [Google](http://google-styleguide.googlecode.com/svn/trunk/objcguide.xml), ...

###Basic Object-Oriented Programming:
- Keywords: Objects, Class, Inheritance, Encapsulation, Polymorphism, Instance Methods vs Class Methods.

	+ If you are familiar with these terms, you can watch [Lecture 3](https://itunes.apple.com/us/course/developing-ios-7-apps-for/id733644550) from [Stanford course](http://www.stanford.edu/class/cs193p/cgi-bin/drupal/syllabus) videos and read the [Programming With Objective-C](https://developer.apple.com/library/mac/documentation/cocoa/conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html#//apple_ref/doc/uid/TP40011210-CH1-SW1) from Apple.

	+ If you are not confident at these terms, unclear about allocation, pointer…, you should play with [Programming in Objective-C](http://www.amazon.com/Programming-Objective-C-Edition-Developers-Library/dp/032188728X) or [The Big Nerd Ranch Guide](http://www.amazon.com/iOS-Programming-Ranch-Edition-Guides/dp/0321821521) book first.

2. Xcode:
---------

- Overview and basic about xcode, Paul Hegarty explains very well about xcode components, how to use IB in [Lecture 2](https://itunes.apple.com/us/course/developing-ios-7-apps-for/id733644550).

- [Working efficiently with Xcode](https://developer.apple.com/videos/wwdc/2012/) in WWDC 2012 teaches some saving-tips and demonstrate workflow to help you work faster and efficiently.

- If you are a fan of Emacs, Xcode already support Emacs typing style. If you are a fan of VIM, you should try [xVim](https://github.com/JugglerShu/XVim) plugin.

- [Hidden iOS7 development gems in iOS7 Tech Talk](http://devstreaming.apple.com/videos/techtalks/2013/18_Hidden_iOS_7_Development_Gems/Hidden_iOS_7_Development_Gems-sd.mov?dl=1) shows some hidden features in Xcode, Objective-C and iOS simulator. 

- Make sure you don’t miss the article from [MengTo](https://twitter.com/MengTo): [The Power of Xcode](https://medium.com/learning-xcode-as-a-designer/afcfd3f9128b)

3. Objective-C programming language
-----------------------------------

- [Categories](https://developer.apple.com/library/mac/documentation/cocoa/conceptual/ProgrammingWithObjectiveC/CustomizingExistingClasses/CustomizingExistingClasses.html#//apple_ref/doc/uid/TP40011210-CH6-SW1), [Protocol](https://developer.apple.com/library/mac/documentation/cocoa/conceptual/ProgrammingWithObjectiveC/WorkingwithProtocols/WorkingwithProtocols.html#//apple_ref/doc/uid/TP40011210-CH11-SW1),  [Block](https://developer.apple.com/library/mac/documentation/cocoa/conceptual/Blocks/Articles/00_Introduction.html#//apple_ref/doc/uid/TP40007502), [KVC](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/KeyValueCoding/Articles/KeyValueCoding.html) / [KVO](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/KeyValueObserving/KeyValueObserving.html#//apple_ref/doc/uid/10000177i), [ARC](https://developer.apple.com/library/ios/releasenotes/ObjectiveC/RN-TransitioningToARC/Introduction/Introduction.html#//apple_ref/doc/uid/TP40011226), [Exception](https://developer.apple.com/library/mac/documentation/cocoa/conceptual/Exceptions/Exceptions.html#//apple_ref/doc/uid/10000012i), [Error](https://developer.apple.com/library/mac/documentation/cocoa/conceptual/ErrorHandlingCocoa/ErrorHandling/ErrorHandling.html#//apple_ref/doc/uid/TP40001806), and [Debugging](https://developer.apple.com/library/ios/technotes/tn2239/_index.html) are very important in Objective-C.

- Working with mobile device is hard job with limited resources. Apple wrote really good document about [Memory Management](https://developer.apple.com/library/ios/documentation/cocoa/conceptual/MemoryMgmt/Articles/MemoryMgmt.html). [Matt Galloway](https://twitter.com/mattjgalloway) explains very clear from ARC to Memory Management with Exception-Safe Code in [his book](http://www.amazon.com/Effective-Objective-C-2-0-Specific-Development/dp/0321917014)(chapter 5), he also shows how to use Zoombies the debug.

- [Objective-C runtime](https://developer.apple.com/library/mac/documentation/cocoa/Conceptual/ObjCRuntimeGuide/Introduction/Introduction.html) makes its [dynamically](http://www.youtube.com/watch?v=vrEoUSuMu_c#t=1015). Apple [opens source](http://www.opensource.apple.com/source/objc4/objc4-437.1/runtime/) it.

- "Many of the programmatic interfaces of the Cocoa and Cocoa Touch frameworks only make sense only if you are aware of the concepts on which they are based" from Apple. So, pls read [The Concept of Objective-C Programming.](https://developer.apple.com/library/ios/documentation/general/conceptual/CocoaEncyclopedia/Introduction/Introduction.html#//apple_ref/doc/uid/TP40010810-CH1-SW1)

- For updated information from Apple. Pls read the [Objective-C Feature Availability Index](https://developer.apple.com/library/ios/releasenotes/ObjectiveC/ObjCAvailabilityIndex/index.html#//apple_ref/doc/uid/TP40012243).

###Foundation: 

- [Peter Steinberger](https://twitter.com/steipete) has a great article about [The Foundation Collection Classes](http://www.objc.io/issue-7/collections.html). 

- [Chris Eidhof](http://twitter.com/chriseidhof) also has a great article about [Value Objects](http://www.objc.io/issue-7/value-objects.html) - usually are models.

- KVC and KVO from [objc.io](http://www.objc.io/issue-7/key-value-coding-and-observing.html), [NSHipster](http://nshipster.com/key-value-observing/) and [how to build KVC](https://www.mikeash.com/pyblog/friday-qa-2013-02-08-lets-build-key-value-coding.html).

- Communication between objects is really important to know. [Florian Kugler](https://twitter.com/floriankugler) has the best [review](http://www.objc.io/issue-7/communication-patterns.html) on this topic.

- [Custom Formatters](http://www.objc.io/issue-7/nsformatter.html), [Linguistic Tagging](http://www.objc.io/issue-7/linguistic-tagging.html) from objC.io are excellent to take a look.

- [Matt](http://mattt.me/) wrote many topics related to this subject. Read it for your [leisure](http://nshipster.com/).

4. Cocoa Design Pattern
-----------------------

About Cocoa Design Pattern, I can’t see any better resource than the [book](http://www.amazon.com/Cocoa-Design-Patterns-Erik-Buck/dp/0321535022) from [Erik M. Buck](http://www.informit.com/authors/bio.aspx?a=9DFD42AB-371E-4809-9484-BCEB7E78871C) and Donald A. Yacktman. This book has [many](http://oleb.net/blog/2010/01/book-review-cocoa-design-patterns/) [good](http://cocoasamurai.blogspot.com/2009/10/book-review-cocoa-design-patterns.html) [review](http://www.amazon.com/Cocoa-Design-Patterns-Erik-Buck/product-reviews/0321535022). Beside that, there are some small topics related to this topic(In Junfeng listings) like Introspection, Toll-Free Bridge, Receptionist pattern…. you can read it on [The Concept of Objective-C Programming.](https://developer.apple.com/library/ios/documentation/general/conceptual/CocoaEncyclopedia/Introduction/Introduction.html#//apple_ref/doc/uid/TP40010810-CH1-SW1)

5. Cocoa Touch
--------------
###UIKit:

- To use essential UIKit control like UITextfield, UIButton…. Pls use [cookbook](http://www.amazon.com/iOS-Programming-Cookbook-Vandad-Nahavandipoor/dp/1449372422)(Chapter 1) and [stackoverflow](http://stackoverflow.com/questions/tagged/ios). It helps you in most cases.

- Lecture 5,6,7 from [Stanford Course](http://www.stanford.edu/class/cs193p/cgi-bin/drupal/syllabus) is very good for introduction to [UIViewController](https://developer.apple.com/library/ios/featuredarticles/ViewControllerPGforiPhoneOS/Introduction/Introduction.html#//apple_ref/doc/uid/TP40007457-CH1-SW1), UINavigationController, UIView and Gestures. Pls read [Lighter View Controllers](http://www.objc.io/issue-1/lighter-view-controllers.html) from [objC.io](http://www.objc.io/) to write testable and clean view controllers.

- [Ricki Gregersen](https://twitter.com/rickigregersen) wrote really nice [article](http://www.objc.io/issue-1/containment-view-controller.html) about "[Custom Container View Controller](https://developer.apple.com/library/ios/featuredarticles/ViewControllerPGforiPhoneOS/CreatingCustomContainerViewControllers/CreatingCustomContainerViewControllers.html)". 

- "[Customizing View Controller Transitions](http://blog.bignerdranch.com/3871-golden-opportunity-custom-transitions/)" is new in iOS7. Pls see [WWDC 2013 Session 218](https://developer.apple.com/wwdc/videos/) and [iOS7 Tutorials book chap 16](http://www.raywenderlich.com/store/ios-7-by-tutorials).

- Using [UITableview](https://itunes.apple.com/us/course/developing-ios-7-apps-for/id733644550)(Lecture 11) is normally not hard but to make it [fast](http://floriankugler.com/blog/2013/5/24/layer-trees-vs-flat-drawing-graphics-performance-across-ios-device-generations) [is](http://www.cocoawithlove.com/2009/09/optimizing-loading-of-very-large-table.html) [hard](http://www.cocoawithlove.com/2009/09/optimizing-loading-of-very-large-table.html).  If you want know try to build UITableview from scratch to understand deeply, take a look at this [blog](https://www.mikeash.com/pyblog/friday-qa-2013-02-22-lets-build-uitableview.html). Many people seem to confuse about register a cell and dequeue it. If you have too, pls read this [tip](http://tinyletter.com/iosdev/letters/ios-dev-tip-50-uitableview-registerclass-forcellreuseidentifier): 

- From iOS6, Apple introduces UICollectionView at [WWDC 2012](https://developer.apple.com/videos/wwdc/2012/)(session 205, 219). [Ash Forrow](http://ashfurrow.com/) wrote in details about UICollectionView in his [book](http://www.amazon.com/iOS-UICollectionView-Complete-Mobile-Programming-ebook/dp/B00CFLTD50). It will help you from zero to hero.

- Apple wrote very good document about [UIScrollView](https://developer.apple.com/library/ios/documentation/windowsviews/conceptual/UIScrollView_pg/Introduction/Introduction.html). [WWDC 2013](https://developer.apple.com/wwdc/videos/)(session 217) gave you the power of scrollView in iOS7. 

###UIKit Dynamics and Motion Effect:

-  [WWDC 2013](https://developer.apple.com/wwdc/videos/) Session 206 Getting Started with UIKit Dynamics

-  [WWDC 2013](https://developer.apple.com/wwdc/videos/) Session 221 Advanced Techniques with UIKit Dynamics

- [iOS7 Tutorials](http://www.raywenderlich.com/store/ios-7-by-tutorials) Chapter 2.

- [Tutorial](http://www.teehanlax.com/blog/introduction-to-uikit-dynamics/) [from](http://www.teehanlax.com/blog/introduction-to-uimotioneffect/) [Ash Forrow](http://ashfurrow.com/). 

###Push Notification

- [Push Notification Guide](https://developer.apple.com/library/ios/documentation/NetworkingInternet/Conceptual/RemoteNotificationsPG/Chapters/ApplePushService.html) from Apple.

- We use [UrbanAirShip](http://urbanairship.com/) at 2359Media. Pls read [dev guide](http://urbanairship.com/resources/developer-resources).

- [Pusher](http://pusher.com/) and [Parse.com](https://parse.com) are good to give a try.

###MapKit:

- Simple example from [cookbook](http://www.amazon.com/iOS-Programming-Cookbook-Vandad-Nahavandipoor/dp/1449372422) Chap 17.

- [WWDC 2012](https://developer.apple.com/videos/wwdc/2012/) (session 300)

- [WWDC 2013](https://developer.apple.com/wwdc/videos/) (session 309, 304)

- [iOS6 Tutorials](http://www.raywenderlich.com/store/ios-6-by-tutorials) Chap 18.

- [iOS7 Tutorials](http://www.raywenderlich.com/store/ios-7-by-tutorials) Chap 23.

- [Mapkit course](https://www.codeschool.com/courses/ios-operation-mapkit) from [codeschool](https://www.codeschool.com/) is awesome to learn by doing.

###Game Center:

- Check out this [list](https://developer.apple.com/game-center/) from apple.

- [iOS6 Tutorials](http://www.raywenderlich.com/store/ios-6-by-tutorials) Chap 13, 14.

- [iOS game by tutorials](http://www.raywenderlich.com/store/ios-games-by-tutorials) book.

###Ads

- [iOS7 Tutorials](http://www.raywenderlich.com/store/ios-7-by-tutorials) Chap 29.

- [WWDC 2011](https://developer.apple.com/videos/wwdc/2011/): Building iAd Rich Media Ads with iAd Producer

- [WWDC 2013](https://developer.apple.com/wwdc/videos/) (session 611, 613, 604, 609)

- [iAd Programming Guide](https://developer.apple.com/library/IOs/documentation/UserExperience/Conceptual/iAd_Guide/Introduction/Introduction.html#//apple_ref/doc/uid/TP40009881) from Apple.

 - [iAd Implementation Best Practices.](https://developer.apple.com/library/IOs/technotes/tn2264/_index.html#//apple_ref/doc/uid/DTS40011827)

- [Sample code](https://developer.apple.com/library/IOs/samplecode/iAdSuite/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010198) from Apple.

###TextKit

- [iOS7 Tutorials](http://www.raywenderlich.com/store/ios-7-by-tutorials) Chap 4,5.

- [WWDC 2013](https://developer.apple.com/wwdc/videos/) (session 210, 223, 220)

- [Text Programming Guide for iOS](https://developer.apple.com/library/IOs/documentation/StringsTextFonts/Conceptual/TextAndWebiPhoneOS/Introduction/Introduction.html#//apple_ref/doc/uid/TP40009542-CH1-SW1).

###AirDrop

- [iOS7 Tutorials](http://www.raywenderlich.com/store/ios-7-by-tutorials) Chap 20.

- [Sample Code](https://developer.apple.com/library/IOs/samplecode/sc2273/Introduction/Intro.html#//apple_ref/doc/uid/DTS40013842) from Apple.

###Auto Layout

- Simple Introduction. Pls read [cookbook](http://www.amazon.com/iOS-Programming-Cookbook-Vandad-Nahavandipoor/dp/1449372422) Chap 3.

- [Auto Layout Guide](https://developer.apple.com/library/ios/documentation/userexperience/conceptual/AutolayoutPG/Introduction/Introduction.html) from Apple.

- WWDC 2012 (session [202](https://developer.apple.com/videos/wwdc/2012/?id=202), [228](https://developer.apple.com/videos/wwdc/2012/?id=228), [232](https://developer.apple.com/videos/wwdc/2012/?id=232)).

- [WWDC 2013](https://developer.apple.com/wwdc/videos/) session 406.

- [In-Depth AutoLayout and UIScrollView](https://developer.apple.com/library/IOs/technotes/tn2154/_index.html#//apple_ref/doc/uid/DTS40013309).

- [Auto Layout performance](http://floriankugler.com/blog/2013/4/21/auto-layout-performance-on-ios).

- [Auto Layout Revisited](http://www.adevelopingstory.com/blog/2013/05/auto-layout-for-ios-revisited.html).

###UI State Preservation

- [iOS doc](https://developer.apple.com/library/ios/documentation/iphone/conceptual/iphoneosprogrammingguide/StatePreservation/StatePreservation.html) from Apple.

- [Simple introduction](http://ideveloper.co/introduction-to-ui-state-preservation-restoration-in-ios6/) from [Matt Tancock](https://twitter.com/mtancock).

- [iOS6 Tutorials](http://www.raywenderlich.com/store/ios-6-by-tutorials) Chap 16.

- WWDC 2012 (session [208](https://developer.apple.com/videos/wwdc/2012/?id=208)).

- [WWDC 2013](https://developer.apple.com/wwdc/videos/) session 222, 101.

- Care about screen brightness, pls read this [Q&A](https://developer.apple.com/library/IOs/qa/qa1751/_index.html#//apple_ref/doc/uid/DTS40013391).

- [Sample](https://developer.apple.com/library/IOs/samplecode/StateRestoreChildViews/Introduction/Intro.html#//apple_ref/doc/uid/DTS40013492) [code](https://developer.apple.com/library/IOs/samplecode/StateRestore/Introduction/Intro.html#//apple_ref/doc/uid/DTS40013190) from Apple.

###Multitasking

- [WWDC 2013](https://developer.apple.com/wwdc/videos/) 204 What’s New with Multitasking.

- [App States and Multitasking](http://d.pr/YB8m/2rcZW9Tt).

- [iOS7 Tutorials](http://www.raywenderlich.com/store/ios-7-by-tutorials) Chapter 17-18.

- [cookbook](http://www.amazon.com/iOS-Programming-Cookbook-Vandad-Nahavandipoor/dp/1449372422) Chap 14

###Gesture Recognizers

- Simple Introduction. Pls read [cookbook](http://www.amazon.com/iOS-Programming-Cookbook-Vandad-Nahavandipoor/dp/1449372422) Chap 8.

- WWDC 2012 session [233](https://developer.apple.com/videos/wwdc/2012/?id=233).

- [Sample](https://developer.apple.com/library/IOs/samplecode/Touches/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007435) [code](https://developer.apple.com/library/IOs/samplecode/SimpleGestureRecognizers/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009460) from Apple.

- [Raywenderlich](http://www.raywenderlich.com/) has a very [nice](http://www.raywenderlich.com/21842/how-to-make-a-gesture-driven-to-do-list-app-part-13) [serial](http://www.raywenderlich.com/21952/how-to-make-a-gesture-driven-to-do-list-app-part-23) [blog](http://www.raywenderlich.com/22174/how-to-make-a-gesture-driven-to-do-list-app-part-33) about this topic.

###Standard System View Controllers:

- Simple example. Pls read [cookbook](http://www.amazon.com/iOS-Programming-Cookbook-Vandad-Nahavandipoor/dp/1449372422) Chap 16.

- Many stuff like: Display or edit contact information, Create or edit calendar events, Compose an email or SMS message, Open or preview the contents of a file, Take a picture or choose a photo from the user’s photo library, Shoot a video clip, .... Pls google it. You will find the shortest way to do this or recommendation opensource.

6. Graphics and Media
---------------------

-For simple introduction. Pls read [cookbook](http://www.amazon.com/iOS-Programming-Cookbook-Vandad-Nahavandipoor/dp/1449372422) Chap 17.

###Core Graphics

- [Quartz 2D](https://developer.apple.com/library/ios/documentation/graphicsimaging/conceptual/drawingwithquartz2d/Introduction/Introduction.html) is a part of Core Graphics. 

- [Core](https://developer.apple.com/library/IOs/qa/qa1706/_index.html#//apple_ref/doc/uid/DTS40010278) [Graphics](https://developer.apple.com/library/IOs/qa/qa1708/_index.html#//apple_ref/doc/uid/DTS40010245) [Q&A](https://developer.apple.com/library/IOs/qa/qa1509/_index.html#//apple_ref/doc/uid/DTS10004216)

- [Sample](https://developer.apple.com/library/IOs/samplecode/QuartzDemo/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007531) [code](https://developer.apple.com/library/IOs/samplecode/ZoomingPDFViewer/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010281) [from](https://developer.apple.com/library/IOs/samplecode/LargeImageDownsizing/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011173) Apple.

- [Smooth drawing](https://www.altamiracorp.com/blog/employee-posts/capture-a-signature-on-ios) using Quartz 2D

###Core Animation

- [Nick Lockwood](https://twitter.com/nicklockwood) wrote great book "[iOS Core Animation Advanced Techniques](http://www.amazon.com/iOS-Core-Animation-Advanced-Techniques-ebook/dp/B00EHJCORC)".

- [Core animation Programming](https://developer.apple.com/library/ios/documentation/cocoa/conceptual/coreanimation_guide/introduction/introduction.html) Guide from Apple.

- [Core animation cookbook](https://developer.apple.com/library/ios/documentation/GraphicsImaging/Conceptual/CoreAnimation_Cookbook/Introduction/Introduction.html#//apple_ref/doc/uid/TP40005406) from Apple.

### Core Image

- [Core Image Programming Guide](https://developer.apple.com/library/IOs/documentation/GraphicsImaging/Conceptual/CoreImaging/ci_intro/ci_intro.html#//apple_ref/doc/uid/TP30001185) from Apple.

- [iOS6 Tutorials](http://www.raywenderlich.com/store/ios-6-by-tutorials) Chap 17.

- WWDC 2012 (session [511](https://developer.apple.com/videos/wwdc/2012/?id=511), [510](https://developer.apple.com/videos/wwdc/2012/?id=510)).

- [WWDC 2013](https://developer.apple.com/wwdc/videos/) session 509).

- [Sample Code](https://developer.apple.com/library/IOs/samplecode/PocketCoreImage/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011220) from Apple.

### OpenGL ES and GLKit

- There are [many document ](https://developer.apple.com/library/IOs/navigation/#section=Frameworks&topic=OpenGLES)from Apple.

- [Erik M. Buck](http://www.informit.com/authors/bio.aspx?a=9DFD42AB-371E-4809-9484-BCEB7E78871C)(author of [Cocoa Design Pattern book](http://www.amazon.com/Cocoa-Design-Patterns-Erik-Buck/dp/0321535022)) wrote great [book](http://www.amazon.com/Learning-OpenGL-iOS-Hands-Programming/dp/0321741838) about OpenGL ES. 

###Core Text

- [Core Text](http://www.raywenderlich.com/4147/core-text-tutorial-for-ios-making-a-magazine-app) Tutorial.

- [Core Text Programming Guide](https://developer.apple.com/library/IOs/documentation/StringsTextFonts/Conceptual/CoreText_Programming/Introduction/Introduction.html#//apple_ref/doc/uid/TP40005533) from Apple.

- [Sample](https://developer.apple.com/library/IOs/samplecode/DownloadFont/Introduction/Intro.html#//apple_ref/doc/uid/DTS40013404) [code](https://developer.apple.com/library/IOs/samplecode/CoreTextPageViewer/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010699) from Apple.

- WWDC 2012 (Session [215](https://developer.apple.com/videos/wwdc/2012/?id=215)).

###Image I/O

-[ Image I/O Programming Guide](https://developer.apple.com/library/IOs/documentation/GraphicsImaging/Conceptual/ImageIOGuide/imageio_intro/ikpg_intro.html#//apple_ref/doc/uid/TP40005462) from Apple.

- [Technical Q&As](https://developer.apple.com/library/IOs/qa/qa1654/_index.html#//apple_ref/doc/uid/DTS40010280).

###AssetsLibrary

- [Sample](https://developer.apple.com/library/IOs/samplecode/MyImagePicker/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010135) [Code](https://developer.apple.com/library/IOs/samplecode/PhotosByLocation/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010136) from Apple.

### Media Player

- [iPod Library Access Programming Guide](https://developer.apple.com/library/IOs/documentation/Audio/Conceptual/iPodLibraryAccess_Guide/Introduction/Introduction.html#//apple_ref/doc/uid/TP40008765) from Apple.

- [Technical](https://developer.apple.com/library/IOs/qa/qa1656/_index.html#//apple_ref/doc/uid/DTS40009076) [Q&As](https://www.google.com/url?q=https%3A%2F%2Fdeveloper.apple.com%2Flibrary%2FIOs%2Fqa%2Fqa1240%2F_index.html%23%2F%2Fapple_ref%2Fdoc%2Fuid%2FDTS40010190&sa=D&sntz=1&usg=AFQjCNFuFTdBHlCNTXHQvnnuoIKIhIbO4w) from [Apple](https://developer.apple.com/library/IOs/qa/qa1661/_index.html#//apple_ref/doc/uid/DTS40009204).

- [Technical note](https://developer.apple.com/library/IOs/technotes/tn2266/_index.html#//apple_ref/doc/uid/DTS40009989).

- [Sample](https://developer.apple.com/library/IOs/samplecode/MoviePlayer_iPhone/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007798) [code](https://developer.apple.com/library/IOs/samplecode/AddMusic/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008845) from Apple.

###AVFoundation

- [AVFoundation Programming Guide](https://developer.apple.com/library/IOs/documentation/AudioVideo/Conceptual/AVFoundationPG/Articles/00_Introduction.html#//apple_ref/doc/uid/TP40010188) from Apple.

- [iOS7 Tutorials](http://www.raywenderlich.com/store/ios-7-by-tutorials) Chap 22.

- There are the [long listings](https://developer.apple.com/library/IOs/navigation/#section=Frameworks&topic=AVFoundation) sample code, technical notes.. from Apple

###OpenAL

- [Guide](http://ohno789.blogspot.com/2013/08/openal-on-ios.html)

- [Sample code](https://developer.apple.com/library/IOs/samplecode/oalTouch/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007769) from Apple.

###Core Audio

- [Core Audio Overview](https://developer.apple.com/library/IOs/documentation/MusicAudio/Conceptual/CoreAudioOverview/Introduction/Introduction.html#//apple_ref/doc/uid/TP40003577)

- [Sample code, technical notes](https://developer.apple.com/library/IOs/navigation/#section=Frameworks&topic=CoreAudio)…. from apple.

###Core Video

###AirPlay

- [AirPlay Overview](https://developer.apple.com/library/IOs/documentation/AudioVideo/Conceptual/AirPlayGuide/Introduction/Introduction.html#//apple_ref/doc/uid/TP40011045).

- [Sample code](https://developer.apple.com/library/IOs/samplecode/GLAirplay/Introduction/Intro.html#//apple_ref/doc/uid/DTS40013259) and [Technical Q&As](https://developer.apple.com/library/IOs/qa/qa1803/_index.html#//apple_ref/doc/uid/DTS40013769).

- WWDC 2011: [AirPlay and External Displays in iOS apps.](https://developer.apple.com/videos/wwdc/2011/includes/airplay-and-external-displays-in-ios-apps.html#airplay-and-external-displays-in-ios-apps)

7. Core Services
----------------

###CoreData

- Apple wrote great article about [CoreData](https://developer.apple.com/library/IOs/documentation/Cocoa/Conceptual/CoreData/cdProgrammingGuide.html#//apple_ref/doc/uid/TP40001075).

- For simple introduction. Pls read [cookbook](http://www.amazon.com/iOS-Programming-Cookbook-Vandad-Nahavandipoor/dp/1449372422) Chap 15.

- There are [some](http://www.amazon.com/Pro-Core-Data-Second-Edition/dp/1430236566) [books](http://pragprog.com/book/mzcd2/core-data) good to read.

- Sample code, videos, Q&As… from [Apple](https://developer.apple.com/library/IOs/navigation/#section=Frameworks&topic=CoreData).

- [Overview CoreData in detail](http://nshipster.com/core-data-libraries-and-utilities/).

- objC.io also wrote great article in [CoreData](http://www.objc.io/issue-4) issue.

###Grand Central Dispatch(GCD)

- [cookbook](http://www.amazon.com/iOS-Programming-Cookbook-Vandad-Nahavandipoor/dp/1449372422)(Chap 6) did great job to introduction to concurrency programming.

- [Matt Galloway](https://twitter.com/mattjgalloway) [book](http://www.amazon.com/Effective-Objective-C-2-0-Specific-Development/dp/0321917014)(Chap 6)

- Apple wrote very nice [Concurrency Programming Guide](https://developer.apple.com/library/ios/DOCUMENTATION/General/Conceptual/ConcurrencyProgrammingGuide/Introduction/Introduction.html).

- objC.io has an i[ssue](http://www.objc.io/issue-2) about this topic. It’s high level.

###In-App Purchase

- [In-App Purchase Programming Guide](https://developer.apple.com/library/IOs/documentation/NetworkingInternet/Conceptual/StoreKitGuide/Introduction.html#//apple_ref/doc/uid/TP40008267) from Apple.

- [Videos, sample code, technical notes](https://developer.apple.com/library/IOs/navigation/#section=Frameworks&topic=StoreKit) from Apple.

- [iOS6 Tutorials](http://www.raywenderlich.com/store/ios-6-by-tutorials) Chap 9,10.

###JavaScriptCore

- [WWDC 2013](https://developer.apple.com/wwdc/videos/?id=615) session 615

- Before iOS7, did the [communication between Javascript and objective-C](https://github.com/phatle/HybridKit-iOS) is very [hard job.](https://github.com/phatle/oncourse) 

###P2P Services

- [iOS7 Tutorials](http://www.raywenderlich.com/store/ios-7-by-tutorials) Chap 21.

- WWDC 2013 [Nearby Networking with Multipeer Connectivity](https://developer.apple.com/wwdc/videos/?id=708)

- [Best practice and limitations ](http://www.slideshare.net/waynehartman/multipeer-connectivity)

###iCloud Storage

- WWDC 2012 (Session [209](https://developer.apple.com/videos/wwdc/2012/?include=209#209), [227](https://developer.apple.com/videos/wwdc/2012/?include=227#227), [224](https://developer.apple.com/videos/wwdc/2012/?include=224#224), [218](https://developer.apple.com/videos/wwdc/2012/?include=218#218), [237](https://developer.apple.com/videos/wwdc/2012/?include=237#237))

- WWDC 2013 Session [207](https://developer.apple.com/videos/wwdc/2013/?id=207).

###Core Location

- [cookbook](http://www.amazon.com/iOS-Programming-Cookbook-Vandad-Nahavandipoor/dp/1449372422)(Chap 7)

- [iOS7 Tutorials](http://www.raywenderlich.com/store/ios-7-by-tutorials) Chap 24

- WWDC 2012 (Session [303](https://developer.apple.com/videos/wwdc/2012/?id=303))

- WWDC 2013 Session [307](https://developer.apple.com/wwdc/videos/?id=307)

- [Sample](https://developer.apple.com/library/IOs/samplecode/GeocoderDemo/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011097) [code](https://developer.apple.com/library/IOs/samplecode/LocateMe/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007801) from [Apple](https://developer.apple.com/library/IOs/samplecode/Teslameter/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008931).

###Core Motion

- WWDC 2012 [Understanding Core Motion](https://developer.apple.com/videos/wwdc/2012/?id=524).

- [Sample ](https://developer.apple.com/library/IOs/samplecode/pARk/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011083)[code](https://developer.apple.com/library/IOs/samplecode/MotionGraphs/Introduction/Intro.html#//apple_ref/doc/uid/DTS40012333) from Apple.

###EventKit

- [Calendar and Reminders Programming Guide](https://developer.apple.com/library/IOs/documentation/DataManagement/Conceptual/EventKitProgGuide/Introduction/Introduction.html#//apple_ref/doc/uid/TP40009765) from Apple.

- [iOS6 Tutorials](http://www.raywenderlich.com/store/ios-6-by-tutorials) Chap 19.

- WWDC 2012 session [304](https://developer.apple.com/videos/wwdc/2012/?id=304).

- [Sample code](https://developer.apple.com/library/IOs/samplecode/SimpleEKDemo/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010160) from Apple.

###Newsstand

- WWDC 2012 session [307](https://developer.apple.com/videos/wwdc/2012/?id=307).

- [iOS5 Tutorials](http://www.raywenderlich.com/store/ios-5-by-tutorials) Chap 13, 14.

###Passbook

-[ Passbook Programming Guide](https://developer.apple.com/library/IOs/documentation/UserExperience/Conceptual/PassKit_PG/Chapters/Introduction.html#//apple_ref/doc/uid/TP40012195) from Apple.

- [iOS6 Tutorials](http://www.raywenderlich.com/store/ios-6-by-tutorials) Chap 7,8.

- [iOS7 Tutorials](http://www.raywenderlich.com/store/ios-7-by-tutorials) Chap 27, 28.

- WWDC 2013 session [301](https://developer.apple.com/videos/wwdc/2012/?id=301), [309](https://developer.apple.com/videos/wwdc/2012/?id=309).

- WWDC 2013 session [302](https://developer.apple.com/wwdc/videos/?id=302), [303](https://developer.apple.com/wwdc/videos/?id=303).

- [Passkit FAQ](https://developer.apple.com/library/IOs/technotes/tn2302/_index.html#//apple_ref/doc/uid/DTS40013009).

8. CoreOS
---------

- [General Tecnology Overview](https://developer.apple.com/library/ios/documentation/miscellaneous/conceptual/iphoneostechoverview/coreoslayer/coreoslayer.html)


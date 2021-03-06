Changelog
=========

###Version 1.4.0
- Added UITextView category
- Added NSObject category
- Added ```BFLogDetailedString``` to get more detailed log string in BFLog class
- Added ```dateInformationDescriptionWithInformation:dateSeparator:usFormat``` method, to get timestamp in NSDate category
- Added ```fileSize:fromDirectory:``` method, to get size of a file in NSFileManager category
- Added some ```@property``` method, to get the RGB single component in UIColor category
- Added ```canProvideRGBComponents, contrastingColor & complementaryColor``` methods in UIColor category
- Added ```imageFromText:font:fontSize:imageSize:``` method, to create an UIImage from a given text in UIImage category
- Fixed UIImage category to support al types of display (Retina & Retina HD)
- Fixed UIImage category to remove all warnings

###Version 1.3.2
- Added in every class or category ```@import``` to import the needed frameworks


###Version 1.3.1
- Added NSDictionary category with ```dictionaryToJson:``` methods
- Fixed ```reversedArray:``` in NSArray category

Thanks to [@simonlinj](https://github.com/simonlinj) for this release


###Version 1.3.0
- Complete rewrite of BFLog class with more details in log and string of all logs
- Added ```APP_DELEGATE``` macro to retrive AppDelegate
- Added Base64 encode/decode
- Added NSThread class with function ```runOnMainThread```
- Added ```RGB & RGBA``` macros to create UIColor objects
- Added missing fonts (iOS 8)
- Added missing Audio IDs
- Added some localized strings


###Version 1.2.0
- Added NSMutableDictionary category
- Added in NSArray the method ```objectAtCircleIndex:```
- Added in BFSystemSound the ability to create and dispose custom sound
- Added BFApp and BFLog classes
- In NSArray the method ```arrayToJson:``` now returns the localized string error
- NSArray & NSMutableArray enhancements

Thanks to [@antwork](https://github.com/antwork) for this release


###Version 1.1.0
- Added UIWindow category
- Added system macros
- Added new iOS devices
- Added pulse animation
- Added Russian, Ukrainian, Indonesian and Chinese
- Minor enhancements & bugfixes

Thanks to [@hiralin](https://github.com/hiralin) & [@bontangster](https://github.com/bontangster) for this release

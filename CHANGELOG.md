## 0.7.3
* Relaxed the environment constraints for the plugin to support flutter v3.22.0

## 0.7.2

* refactor(android): improved build and code optimization
  - Refactored the Android part to enhance the build process.
  - Fixed warning related to unchecked operations.
  - Optimized code for better clarity and maintainability.

## 0.7.1
* Thanks for Andrew-Bekhiet
  - Fix memory leak, upgrade gradle wrapper
* Thanks for agufagit
  - build(ios): podspec file name and s.name needs to be same as library name
* Thanks for ettaegbe
  - Update build.gradle added namespace to support new gradle

## 0.7.0
* Refactor code
* Update dependencies and libraries to the latest versions

## 0.6.1
* Thanks for Alberto-Monteiro
  - refactor code

## 0.6.0
* Thanks for Alberto-Monteiro
  - refactor code

* Thanks for Alberto-Monteiro
  - **Breaking change**: `VideoThumbnail.thumbnailFile` now returns `Future<XFile>` instead of `Future<String?>`
  - **Breaking change**: `VideoThumbnail.thumbnailData` now returns `Future<Uint8List>` instead of `Future<Uint8List?>`
  - migrating to use platform interface
  - add web implementation

## 0.5.3
* Thanks Ajb Coder for:
  -   Fix: IOException on runtime
  -   Fix: IOException
  -   Added IOException to catch with RuntimeException
  -   Update dart min sdk to 2.16.0
  -   Upgrade the android compileSdkVersion to 33
* Bump to 0.5.3

## 0.5.2
* Revert the IOException change which causes compiling error on new Android Studio
* Bump to 0.5.2

## 0.5.1
* Add IOException for Android (Thanks k1zerX)
* Fix boolean value issue and enlarge the time window (Thanks niketatjombay) 
* Bump to 0.5.1

## 0.5.0

* Make the `thumbnailFile` to save image in the cache folder if the `path` is `null` for not file based video
* Add HTTP headers for not file based video
* Bump to 0.5.0

## 0.4.6

* Thanks for julek-kal, Nailer, nilsreichardt
* fix setDataSource for Android 11
* Fetch closest frame instead of closest keyframe
* Fix typo specify in video_thumbnail.dart
* Change version and bump to 0.4.6

## 0.4.3

* Migrate to flutter embedding v2 for Android ( Thanks wangbo4020 )
* Bump to 0.4.3

## 0.3.3

* Revert the 0.3.2, bump version to 0.3.3

## 0.3.1

* Fix some null safety warnings, bump version to 0.3.1

## 0.3.0

* Add the null safety support ( Thanks leynier41@gmail.com ), bump version to 0.3.0

## 0.2.5+1

* Fix the typo in iOS ( Thanks ztsyyb <1194234257@qq.com> )

## 0.2.5

* Two enhancement

## 0.2.4

* Fix the missing 'platforms' issue

## 0.2.3

* Generate the thumbnails in a background thread for iOS (Thanks for Hafeez Ahmed)

## 0.2.2

* Fix memory leak ( Thanks for Grigori )
* Additional potential memory leak fix

## 0.2.1

* Remove logging out the setDataSource to prevent leaking the video URL
* Accept the file source with the 'file://' prefix
* Give all default values to make it more user friendly

## 0.2.0

* Breaking change: Switch the `maxHeightOrWidth` to `maxHeight` and `maxWidth`

## 0.1.7

* Generate the thumbnail asynchronously on Android. ( Thanks for Tairs Rzajevs )
## 0.1.6

* Add timeMs, use getScaledFrameAtTime to eliminate image scaling if Android API level >= 27
## 0.1.5+1

* Minor updates
## 0.1.5

* Add repository and issue tracker link and bump version to 0.1.5
## 0.1.3+5

* Fix compiler warning
## 0.1.3+4

* Fix "src/dsp/dsp.h" couldn't find issue due to Podfile has "use_frameworks!"
## 0.1.3+3

* Fix the screen shots url issue
## 0.1.3+2

* Add some screen shots
## 0.1.3

* Bump the version
## 0.0.3

* Add test case
## 0.0.2

* Add webp support for iOS
## 0.0.1

* initial release for this flutter plugin.

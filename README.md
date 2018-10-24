# iOS APP ICONS Generator

### Description
ios-icon-generator is a shell script which aim to generate iOS/macOS/watchOS APP icons easier and simply.
![image](https://github.com/smallmuou/ios-icon-generator/blob/master/ios-icon-generator.gif)
<pre>
VERSION: 2.0.0
USAGE:
    ./ios-icon-generator.sh srcfile dstpath

DESCRIPTION:
    This script aim to generate iOS/macOS/watchOS APP icons easier and simply.

    srcfile - The source png image. Preferably above 1024x1024
    dstpath - The destination path where the icons generate to.

AUTHOR:
    smallmuou<smallmuou@163.com>

EXAMPLE:
    ./ios-icon-generator.sh 1024.png ~/123

</pre>

### Usage

```bash
git clone https://github.com/smallmuou/ios-icon-generator
cd ios-icon-generator
chmod 777 ios-icon-generator.sh
./ios-icon-generator 1024.png ~/output
```

3. Run
	
```bash
smou:ios-icon-generator $ ./ios-icon-generator.sh 1024.png ~/output
[INFO] Generate Icon-16.png ...
[INFO] Generate Icon-16@2x.png ...
[INFO] Generate Icon-32.png ...
[INFO] Generate Icon-32@2x.png ...
[INFO] Generate Icon-128.png ...
[INFO] Generate Icon-128@2x.png ...
[INFO] Generate Icon-256.png ...
[INFO] Generate Icon-256@2x.png ...
[INFO] Generate Icon-512.png ...
[INFO] Generate Icon-512@2x.png ...
[INFO] Generate Icon-20@2x.png ...
[INFO] Generate Icon-20@3x.png ...
[INFO] Generate Icon-29@2x.png ...
[INFO] Generate Icon-29@3x.png ...
[INFO] Generate Icon-40@2x.png ...
[INFO] Generate Icon-40@3x.png ...
[INFO] Generate Icon-60@2x.png ...
[INFO] Generate Icon-60@3x.png ...
[INFO] Generate Icon-76@2x.png ...
[INFO] Generate Icon-83.5@2x.png ...
[INFO] Generate Icon-1024.png ...
[INFO] Congratulation. All icons for iOS/macOS/watchOS APP are generate to the directory: /Users/smou/output.
```
PS: You can find out the icons in ~/output directory.

### Refer
* [iOS Icons Size](https://developer.apple.com/design/human-interface-guidelines/ios/icons-and-images/app-icon/)
* [macOS Icons Size](https://developer.apple.com/design/human-interface-guidelines/macos/icons-and-images/app-icon/)	
* [watchOS Icons Size](https://developer.apple.com/design/human-interface-guidelines/watchos/icons-and-images/home-screen-icons/)

### History
* 2.0.0
    * Update iOS icons size
    * Support macOS icons size
    * Support watchOS icons size
    * Remove ImageMagick Dependency
    * Update code structure for add size more easy.

* 1.0.0
	* Generate all size icons for iPhone and iPad.

### License
This script follow MIT license.

### Contact
If you have any question with using it, you can email to me. My email is: lvyexuwenfa100@126.com

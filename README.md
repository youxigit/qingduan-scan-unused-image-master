# scan-unused-image

This shell script is used to check and clean unused image file in your project  directory，supoort Android and IOS. 
Show the unused image's path and size
At the end show the total unused images count and total size

## show unused image file

    ./scan-unused-image -p /path/of/your/project
The '~/FlashScreen-568h@2x.png' was not referenced in any file ,the file size = 875KB

The shell script work at xcasset,even png in the imageasset ,it can be check out.

============= Total 2 unused image files And Total Size = 887KB =============
## show and clean unused image file

    ./scan-unused-image -r -p /path/of/your/project

##create table show scan results
**please use Numbers open the file unused-image.csv**

![](https://raw.githubusercontent.com/youxigit/qingduan-scan-unused-image-master/master/scan-result.png)

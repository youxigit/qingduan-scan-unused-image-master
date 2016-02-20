# scan-unused-image

This shell script is used to check and clean unused image file in your project  directory，supoort Android and IOS. 
Show the unused image's path and size
At the end show the total unused images count and total size
## show unused image file

    ./unused-image.sh -p /path/of/your/project
The '~/FlashScreen-568h@2x.png' was not referenced in any file ,the file size = 875KB

## show and clean unused image file

    ./unused-image.sh -r -p /path/of/your/project

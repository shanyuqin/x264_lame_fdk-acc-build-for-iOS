# x264_lame_fdk-acc-build-for-iOS

## x264编译的时候如果遇到下列问题,
building x86_64...
Found no assembler
Minimum version is yasm-1.2.0  或者  nasm

请安装yasm 或  nasm 
brew install nasm


ffmpeg 使用x264，fdk-aac 做插件的时候要注意如下两个位置
![文件目录](https://github.com/shanyuqin/x264_lame_fdk-acc-build-for-iOS/blob/master/ffmpeg-img1.png)
![脚本改写](https://github.com/shanyuqin/x264_lame_fdk-acc-build-for-iOS/blob/master/ffmpeg-img2.png)

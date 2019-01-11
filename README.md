# ORB_matching_C
This is an ORB feature point extraction and matching code written in pure C language.
The basic framework refers to https://github.com/chenpeikai/sift.
# Created by SwChui on 2019/1/10.
#Copyright © 2019年 SwChui. All rights reserved.

运行步骤：
1. 打开终端
2. 运行./ORB_Matching指令即可在运行目录下生成orbmatching_results.bmp
3. 打开orbmatching_results.bmp查看ORB特征点及匹配结果

相关文件说明：
1. 1.bmp和2.bmp为输入图片
2. reference.bmp为参考运行结果图片
3. ORB_Mathcing为编译生成运行文件
4. 压缩文件为项目源码

代码编译运行步骤：
1. 如需编译调试代码，请将压缩文件解压
2. 请使用Xcode打开ORB_Matching.xcodeproj文件
3. 请将1.bmp及2.bmp拷贝至x打开项目debug目录下（右键左栏project下结果文件，打开所在目录）
4. 点击编译即可在debug目录下生成运行结果图片

Operation steps:
1. Open the terminal
2. Running ./ORB_Matching command can generate orbmatching_results.bmp in the run directory
3. Open orbmatching_results.bmp to view the ORB feature points and matching results

Related document description:
1. 1.bmp and 2.bmp are input images
2. reference.bmp refers to the picture of operation results
3. ORB_Mathcing generates run files for compilation
4. Compressed file for the project source code

Code compilation and running steps:
1. If you need to compile debugging code, please extract the compressed file
2. Please use Xcode to open the orb_match.xcodeproj file
3. Please copy 1. BMP and 2.
4. Click "compile" to generate the running result pictures in the debug directory
5. If you want to compile this project on another platform, you will need to reset the compilation options for your own platform

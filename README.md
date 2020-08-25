# libstdcForXcode10
更新到 Xcode11

针对Xcode10下因为缺少libstdc++导致编译失败

iPhoneOS文件夹下的所有库，复制到/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS.sdk/usr/lib

iPhoneSimulator文件夹下的所有库，复制到/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator.sdk/usr/lib

RuntimeRoot文件夹下的所有库，复制到/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib

注意Xcode11下RuntimeRoot文件夹路径修改了 ，改为/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib


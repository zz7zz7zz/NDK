# NDK

一、JNI开发基础知识

    1.JNI基础知识

    2.注意事项

      2.1.DelLocalRef/DelGloalRef
      2.2.GetxxxElements/ReleasexxxElements
      2.3.类型
      2.4.JNI_Onload与注册本地函数

    3.类型转换

    4.JNI_Onload与注册本地函数
    
    5.阅读官方demo（HelloJNI，HelloJNICallack，Hello-libs）
    
    6.遇到崩溃时定位代码行方法
    
 https://docs.oracle.com/javase/7/docs/technotes/guides/jni/spec/jniTOC.html

 https://developer.android.com/training/articles/perf-jni
 
 
 二、C/C++基础知识
    
    std c++ 98 / std c++ 11 /std c++ 14 三者区别
    
    线程知识PThread
    
    cmake知识
    
三、实战
  
  项目一：使用Native获取签名并且验证(libsignature.so)。
  
  项目二：使用Native编写Socket长连接，需要熟悉Select，Poll，EPoll区别(libsocket.so)。
  
  项目三：使用Native编写ffmpeg功能(libFFmpegCmd.so，libFFmpegMain.so)。
  
        a.编译ffmpeg源码，生成so库文件，再自己编写FFmpegCmd.so实现通过命令行实现ffmpeg功能。
        
        b.编译ffmpeg源码，生成so库文件，再自己编写FFmpegMain.so通过ffmpeg的api实现给视频文件添加水印功能/视频裁剪功能。
  
  https://github.com/wxmylife/JNI_RSA_Sign

  https://www.jianshu.com/p/3d5be02616f4

  https://cmake.org/cmake/help/latest/command/add_library.html

  https://google.github.io/android-gradle-dsl/current/com.android.build.gradle.internal.dsl.ExternalNativeCmakeOptions.html
  
    
    
    
   
 

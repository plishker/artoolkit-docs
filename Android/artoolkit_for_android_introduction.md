#ARToolkit for Android Introduction

ARToolKit is a computer vision library that provides the tracking functionality required to build augmented reality applications. It has been ported to various hardware and software platforms, with recent focus specifically on the mobile domain.

This section of the ARToolworks support library describes the port of ARToolKit4 to the [Android][1] mobile platform. Android is an open-source software stack for mobile devices that provides the operating system, as well as middleware, key applications and APIs. In addition to the appeal of the open environment, Android has also seen an increasing consumer market share, making it an attractive platform for commercial apps and advertising.

For application development, Android offers a rich [SDK][2] and development tools, based around the Java programming language. While Java is sufficient for the majority of applications, the JNI framework (Java Native Interface) can be used to implement parts of a Java application in C/C++. The [NDK][3] (Native Development Kit) provides the necessary tools, headers and libraries to take advantage of JNI on Android. There are two major motivations for using native code: to potentially increase performance, and to reuse existing C/C++ libraries. In the case of porting ARToolKit to Android, both these motivations come into play.

This guide covers the structure of the ARToolKit port and how to use it to develop your own augmented reality applications on Android. The SDK offers several different development paths depending on the developer’s preference for Java or native coding. A certain amount of prior knowledge of Android development is essential, and assumed.

[1]: http://developer.android.com/index.html
[2]: http://developer.android.com/sdk/index.html
[3]: http://developer.android.com/sdk/ndk/overview.html
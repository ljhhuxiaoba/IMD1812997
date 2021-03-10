#关于Flutter
##什么是Flutter
Flutter是Google一个新的用于构建跨平台的手机App的SDK。写一份代码，在Android 和iOS平台上都可以运行。
##跟React Native、Weex等有什么不同？
React Native、Weex等一直存在一个问题，就是性能跟原生App存在很大的差异。这跟它们的原理有很大的关系，下面从原生App，RN、Weex，Flutter的简单原理说一下它们的不同。
胡小巴:
跟React Native、Weex等有什么不同？
React Native、Weex等一直存在一个问题，就是性能跟原生App存在很大的差异。这跟它们的原理有很大的关系，下面从原生App，RN、Weex，Flutter的简单原理说一下它们的不同。
原生App
苹果2008年发布iOS，Google 2009年发布Android，它们的SDK是基于两种不同的编程语言Objective-C 和 Jave.现在又有了Swift和Kotlin。
WebViews
最早的跨平台方案是基于JaveScript 和 WebView的，像PhoneGap、Cordova、Ionic等。
React Native
RN不仅桥接系统服务，也将系统UI也桥接到了JaveScript中，这样写出来的UI最终也会渲染成原生的控件。
Flutter
Flutter使用Dart语言开发，Dart可以被编译（AOT）成不同平台的本地代码，让Flutter可以直接和平台通讯而不需要一个中间的桥接过程，从而提高了性能。




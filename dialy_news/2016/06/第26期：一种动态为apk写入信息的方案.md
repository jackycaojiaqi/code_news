# 第26期：一种动态为apk写入信息的方案

## 推荐

[Android Developers Backstage：Google Android 团队成员录制的面向 Android 开发者的专业播客](http://diycode.cc/topics/130)

播客 (podcast) 是一种只有声音的网络传播形式，类似于录制的电台节目。Android Developers Backstage 是由 Google Android 团队成员录制的面向 Android 开发者的专业播客，从 2013 年 11 月至今已发布 50 期。

## Android开发

0、[一种动态为apk写入信息的方案](http://pingguohe.net/2016/03/21/Dynimac-write-infomation-into-apk.html)

Android使用的apk包的压缩方式是zip，与zip有相同的文件结构，在zip的Central directory file header中包含一个File comment区域，可以存放一些数据。File comment是zip文件如果可以正确的修改这个部分，就可以在不破坏压缩包、不用重新打包的的前提下快速的给apk文件写入自己想要的数据。

1、[一张图读懂RxJava中的线程控制](http://mp.weixin.qq.com/s?__biz=MzA4NTg1MjM0Mg==&mid=509777575&idx=1&sn=9ace4885f32a1f274e4be8d839700486&scene=0&previewkey=nzeuLjmwTmgy6%2FZhzIm6qswqSljwj2bfCUaCyDofEow%3D)

RXJava一大引人注目的特性就是它便捷的线程切换操作，那么当我们使用subscribeOn和observeOn切换线程时到底发生了哪些事情呢?一起来了解一下吧！

2、[你必须弄懂的Intent Filter匹配规则](http://blog.csdn.net/mynameishuangshuai/article/details/51673273)

 Intent解析机制主要是通过查找已注册在AndroidManifest.xml中的所有IntentFilter及其中定义的Intent，最终找到匹配的Intent，想了解匹配的具体过程和细节吗，你需要看看这篇文章～

3、[教你写一个炫酷的Material Design风格的登录和注册页面](http://tikitoo.github.io/2016/05/17/beautiful-android-login-and-signup-screens-with-material-design-zh/)

一步一步教你写出Material Design风格的界面风格，有兴趣的童鞋还可以自行拓展优化完善！

4、[SineView：正弦曲线的自定义View动画效果](https://github.com/guiguegon/SineView)

![](https://github.com/guiguegon/SineView/raw/master/screenshots/animating.gif)


## 课外话题

[Mary Meeker 发布的《2016年互联网趋势报告》中都有哪些亮点？](https://www.zhihu.com/question/47012694)

作为互联网行业从业者，关注互联网发展趋势自然必不可少！


## 喜欢Diycode每日精选么？喜欢的话，不妨点个 **[Star](https://github.com/DiyCodes/code_news)** 吧！


## 邮箱订阅

想要订阅我们的日报么，来[猛戳这里](http://list.qq.com/cgi-bin/qf_invite?id=d469993d2c888e971c0fbb2309c4d84256968386b126b967)

**如果你是一个爱写技术博客的童鞋，欢迎发稿时在微博@上小编哦，优秀的文章能让更多童鞋们看到！小编：**[D_clock爱吃葱花](http://weibo.com/2480694892/profile?rightmod=1&wvr=6&mod=personinfo&is_all=1)

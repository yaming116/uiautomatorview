
##### 使用方式：
方式1.直接下载根目录下的uiautomatorviewer.jar,替换你本地的${ANDROID_HOME}/tools/lib下的uiautomatorviewer.jar即可

方式2.执行gradle jar命令(或gradlew jar)，编译工程，将build目录下编译出来的uiautomatorviewer.jar替换你本地的${ANDROID_HOME}/tools/lib下的uiautomatorviewer.jar即可

##### 背景：
在做UI自动化时必不可少需要使用到uiautomatorviewer这个工具，但是有时候我们进行元素定位的时候希望使用xpath定位，而这个 工具自身并没提供，为了方便自动生成xpath。在网上找到的方法感觉不是很完整，于是打算自己亲自对该工具进行二次开发。
- 开发环境：
    - ide:intellij idea
    - 编译环境：gradle
    - 语言环境：java
    - 还要必不可少的android sdk
    
##### 下载源码
- 下载[uiautomatorviewer源代码](https://android.googlesource.com/platform/tools/swt/+/marshmallow-mr3-release/uiautomatorviewer/)

```
这些jar可以到你本地的${ANDROID_HOME}/tools/lib中找到
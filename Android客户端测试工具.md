前提：非常重要！！！！！

在对安卓客户端进行测试之前，必须要装好Java JDK，Android SDK。以下许多工具的使用也都基于环境。

工具：

apktool-拆解Apk文件，反编译其中的资源文件，将它们反编译为可阅读的AndroidManifest.xml文件和res文件。下载地址https://bitbucket.org/iBotPeaches/apktool/downloads

smali2java：可以将smali代码反编译成java代码。直接使用smali2java打开apk文件，即可反编译回Java代码。http://download.csdn.net/download/flyingsir_zw/7712571

dex2jar，将dex文件转化成jar。

jd-gui，可以查看jar中的类，其实他就是解析class文件。

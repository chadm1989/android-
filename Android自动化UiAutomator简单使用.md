###UiAutomator简单使用###
####环境搭建
 - 1、安装JDK并添加环境变量。
        安装后，一定要通过JAVA_HOME的方式添加环境变量，即先建立JAVA_HOME变量，然后在path中添加%JAVA_HOME%\bin;
 - 2、添加SDK环境变量。
        一定要先建立ANDROID_HOME，然后把%ANDROID_HOME%\tools添加到path中；
 - 3、安装Eclipse，并安装ADT插件。
 - 4、安装ANT工具，并添加环境变量。同样一定要先建立%ANT_HOME%变量，然后在path中添加%ANT_HOME%\bin
    在CMD下面执行ant指令，如提示Buildfile : build.xml does not exist!则表示成功

###操作步骤改进UiAutomatorHelper###

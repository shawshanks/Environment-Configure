## 安装
[Windows 10 配置Java 环境变量](https://www.runoob.com/w3cnote/windows10-java-setup.html)

## 腾讯云端开发
[最极客的云端开发体验](https://studio.dev.tencent.com/)

## 手动编译运行
```
javac 文件名.java
java 文件名（无任何后缀）
```
### 手动编译运行乱码
[sublime编写java程序保存编译，运行之后中文显示乱码](https://my.oschina.net/ShellingW/blog/837791)

原因：sublime编辑器会默认使用UTF-8编码中文， 而中文环境下编译，OS默认使用GBK编码. UTF-8编码使用GBK编码展现,自然会显示乱码.

解决办法:
  在java程序编译时，使用-encoding命令:  `javac -encoding utf-8 XXX.java`，这样java在进行编译的时候就会知道它需要以uft-8的编码规则进行编译。
  故输出前后编码规则统一就可以解决中文字符乱码问题。

## sublime 配置快速运行    
[Sublime Text3直接编译C、java、C++程序](https://blog.csdn.net/meiqi0538/article/details/83018495)

[sublime配置java运行环境](https://www.jianshu.com/p/bd860d8fd1b8)


### problem
1. 问题显示
 运行`javac ...`时 显示 ???
2. 问题排查
 

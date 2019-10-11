# Override
Here is a record of the common problems encountered in Android development and how they have been solved elegantly and simply

本项目旨在优雅的解决Android开发中遇到的各种问题

## feature

- 基于androidx
- 模块分离，需要哪个功能就拷贝哪个
- 每一个问题都会配有一篇文章
- 请注意，这不仅仅是轮子

## Module

下面是各个模块的功能介绍，每个功能都介绍的非常详细

------------------------------------------------------------

### 1. any_library

这里放了一些常用的工具类

- File相关

  [FileDirUtil.java](any_library/src/main/java/com/utils/library/file/FileDirUtil.java)    文件目录工具
  
  [Fileutils.java](any_library/src/main/java/com/utils/library/file/FileUtils.java)        文件操作工具
  
- io相关

  [IoUtils.java](any_library/src/main/java/com/utils/library/io/IoUtils.java)
  
- 动态权限相关

  [Permissions.java](any_library/src/main/java/com/utils/library/permission/Permissions.java)   动态权限请求类

**相关文章**

- [优雅的解决Android运行时权限问题](any_library/yellow/优雅的解决Android运行时权限问题.md)，[csdn](https://blog.csdn.net/u011077027/article/details/100694123)
- 优雅的hook私有方法
- 如何优雅的使用代理模式封装网络请求和图片加载



### 2. dbframework

手撸数据库框架

- [Android徒手撸数据库系列——注解与反射数据库关系模型](any2_dbframwork/zmark/mark1.md)
- [Android徒手撸数据库系列——实现单表的增删改查](any2_dbframwork/zmark/mark2.md)
- [Android徒手撸数据库系列——多用户分库的实现](any2_dbframwork/zmark/mark3.md)




### 3. git教程
- [一套完整git的PPT教程](git_markdown/git_markdown.pptx)
- [git合并多个commit](git_markdown/git合并多个commit.md)



### 4. 网络相关

```
[Android 生成p10请求]()

[Android 合成p12证书]()

[okHttp单向和双向请求]()
```

相关文章

- [keytool命令详解--学习自签名证书就看这篇](cipher/yellow/keytool命令详解.md)

- [Android 生成pkcs10(csr)请求](cipher/yellow/PKCS10.md)

- [Android 合成pkcs12证书](cipher/yellow/PKCS12.md)

  

### 5. 加解密相关







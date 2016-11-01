[TOC]
# Android简介

```
应用程序 (App开发者)
应用程序框架层 （框架开发者）
库 + Android Runtime （rom 定制）
Linux 内核 (系统开发，开发另外一个系统)

```
**解读： **
# 开发环境
Android Studio

# Activity
**一个可以直接与用户打交道的应用级组件。**

**Activity 做为系统级组件，必须在 Android 应用的配置文件 AndroidManifest.xml 中声明，才能够被 Android 调用**

生命周期
actived paused stopped killed
开发人员必须详细的了解声明周期。官方文档讲的很清楚了，自己学习吧。

**防止屏幕切换方向过程中发生Activity销毁再重建**
AndroidManifest.xml
```xml
android:configChanges="oritentation|keyboardHidden""
```

## Activity管理
栈方式
基于 Android 特有的运行环境和运行方式决定的。性能优化。


# 界面布局
View ViewGroup

# 资源管理
默认资源的存放
特定资源的存放
**不允许开发人员创建自己的资源存放路径**
res 资源文件 打包成二进制
assets 不是资源，只是一些应用必需的辅助支持文件

# Intent 组件
负责对应用中一次操作的动作及动作相关的数据进行描述。
作用： 指令传输

Intent 实现了调用者与被调用者之间的解耦。


# Service

# BroadcastReceiver
# Content Provider
# Fragment
# 基本UI组件
# 高级UI组件
# Menu
# ActionBar
# 通知
# Dialog
# Alarm
# 触控
# 深入View
# 线程与进程
# Preferences
# 文件操作
# 数据库
# 综合实力



















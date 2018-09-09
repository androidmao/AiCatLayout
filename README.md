# Android仿支付宝扫码界面-AiCatLayout

[![JitPack](https://img.shields.io/badge/%20JitPack%20-1.0-5bc0de.svg)](https://jitpack.io/#androidmao/AiCatLayout/1.0)

## 简介:

AiCatLayout是一个仿支付宝扫描二维码布局。

## 特点功能:

 - 动画平缓


## 使用说明
#### 1.在 build.gradle 中添加依赖
```
implementation 'com.github.androidmao:AiCatLayout:1.0'
```

#### 2.在XML布局文件中添加 
```xml
<com.aicat.layout.library.scanner.ScannerCameraMask
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        app:cm_scannerBoxAngleColor="@color/colorScanner"
        app:cm_topMargin="120dp" />
```

#### 3.在 Activity 或者 Fragment 中添加代码
```java

```


License
-------

    Copyright 2018 AndroidMao

  

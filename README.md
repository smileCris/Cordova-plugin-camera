# Cordova-plugin-camera
Cordova使用相机插件
官方文档地址 
[点击查看](http://cordova.axuer.com/docs/zh-cn/latest/reference/cordova-plugin-camera/index.html)
#### 新建Cordova应用
```
$ cordova create camera-demo come.cris.camera cameraDemo
```
PS：依次对应文件夹名，包名，应用名
####  添加安卓平台
```
$ cordova platform add android --save
```
#### 添加camera插件
```
$ cordova plugin add cordova-plugin-camera
```
使用cordova platform ls和cordova plugin ls命令可检查当前平台设置状况以及安装的插件
#### 使用方法
官方提供了这些API

![cameraAPI.png](https://upload-images.jianshu.io/upload_images/14153155-81fd28b004c26a12.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 运行
```
$ cordova run android
```

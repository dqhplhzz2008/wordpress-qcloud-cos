# wordpress-qcloud-cos

本插件的原作者射雕天龙，更新截止时间为2015-11-14
目前已经失效了，后经sy-records更新了一下。
使用腾讯云对象存储服务 COS 作为附件存储空间的WordPress插件，本插件核心功能使用了腾讯云COS官方SDK。

## 插件特色

* 使用腾讯云对象存储服务存储wordpress站点图片等多媒体文件
* 可配置是否上传缩略图和是否保留本地备份
* 本地删除可同步删除腾讯云上面的文件
* 支持腾讯云云存储服务绑定的个性域名

github项目地址:  [https://github.com/dqhplhzz2008/wordpress-qcloud-cos](https://github.com/dqhplhzz2008/wordpress-qcloud-cos)


## 安装
### 直接下载源码
从github下载源码，通过WordPress后台上传安装，或者直接将源码上传到WordPress插件目录`wp-content\plugins`，然后在后台启用。

## 修改配置
* 方法一：在WordPress插件管理页面有设置按钮，进行设置
* 方法二：在WordPress后台管理左侧导航栏`设置`下`腾讯云cos设置`，点击进入设置页面

## 特别说明
* 本插件仅支持`PHP 5.4+`版本
* 推荐使用腾讯云`cos v5`版本
* WordPress后台设置时，`Bucket设置`的input框只需填写桶名，无需带上`-你的APPID`

## 截图
![设置页面](https://raw.githubusercontent.com/dqhplhzz2008/wordpress-qcloud-cos/master/screenshot-1.png)

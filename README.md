## 黄重庆的简历



前提: 已安装`nodejs` `cnpm`
- 0、`cnpm install`安装依赖
- 1、编辑`/src/index.html`文件
- 2、命令行运行`npm run rebuild`
- 3、打开`/index.html`进行预览

![](http://upload-images.jianshu.io/upload_images/4340772-ed3e2e3661349b8c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


> chrome浏览器 - "打印" - 设置无边距 - 即可导出

![黄重庆-简历](http://upload-images.jianshu.io/upload_images/4340772-4b33991783521608.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

注：简历模板基于https://github.com/mcc108/resume


## errors

### ERROR in Node Sass does not yet support your current environment: Windows 64-bit with Unsupported runtime (57)
* 2017-12
最近在学eggJs，只支持node V8以上的版本，所以node升级为8.X版本，运行此项目是报错了，我查了下原因，主要是：**目前有的库并不支持node8.X版本，所以我安装了两个个node版本**
* **当运行此项目是切换到v6.10.3**！！！！


```
// 我目前版本
$ node -v
v8.9.1
$ node -v
v6.10.3  // 当运行此项目是切换到v6.10.3 

```

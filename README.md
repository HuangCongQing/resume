## 黄重庆的简历

[@2018postgraduate](https://github.com/HuangCongQing/resume/tree/postgraduate)

前提: 已安装`nodejs` `cnpm`
- 0、`cnpm install`安装依赖
- 1、编辑`/src/index.html`文件
- 2、命令行运行`npm run rebuild`
- 3、打开`/index.html`进行预览

![](http://upload-images.jianshu.io/upload_images/4340772-ed3e2e3661349b8c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


> chrome浏览器 - "打印" - 设置无边距 - 即可导出

![黄重庆-简历](https://raw.githubusercontent.com/HuangCongQing/resume/18ed9c32bf317665ecd41b21a4c98b1ed233ab74/%E7%AE%80%E5%8E%86%20_%20%E9%BB%84%E9%87%8D%E5%BA%86%20-%20HuangChongqing_%E9%A1%B5%E9%9D%A2_1.jpg)

注：简历模板基于https://github.com/mcc108/resume


## errors

### ERROR in Node Sass does not yet support your current environment: Windows 64-bit with Unsupported runtime (57)
最近在学eggJs，只支持node V8以上的版本，所以node升级为8.X版本，运行此项目是报错了，我查了下原因，目前有的库并不支持node8.X版本，所以我安装了两个个node版本
* **当运行此项目是切换到v6.10.3**！！！！


```
// 我目前版本
$ node -v
v8.9.1
$ node -v
v6.10.3  // 当运行此项目是切换到v6.10.3 
```

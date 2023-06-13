# 搭建私人图床

## 创建图床托管仓库

+ 建议使用国内的Gitee仓库搭建，国外的Github网络慢且不开VPN的话不一定可以访问

注册账号、登录并创建一个仓库

+ 以下是用Gitee作为图床托管仓库

    + ![](https://gitee.com/mood1235/mapimg/raw/master/img/01.png)

    + 创建仓库之后需要上传一个文件，因为空的仓库不能开源，仓库必须开源才能将转换成markdown地址的图片看到
    + 创建仓库![](https://gitee.com/mood1235/mapimg/raw/master/img/2.png)

    + ![](https://gitee.com/mood1235/mapimg/raw/master/img/3.png)
        + 若是第一次使用Git需要进行Git的全局设置![](https://gitee.com/mood1235/mapimg/raw/master/img/Git%E5%85%A8%E5%B1%80%E8%AE%BE%E7%BD%AE.png)

    + 对仓库进行开源

        ![](https://gitee.com/mood1235/mapimg/raw/master/img/%E5%BC%80%E6%BA%9001.png)

    ![](https://gitee.com/mood1235/mapimg/raw/master/img/%E5%BC%80%E6%BA%9002.png)

    + 开源之后需要生成新的令牌

        ![](https://gitee.com/mood1235/mapimg/raw/master/img/%E4%BB%A4%E7%89%8C01.png)

        ![](https://gitee.com/mood1235/mapimg/raw/master/img/%E4%BB%A4%E7%89%8C02.png)

        ![](https://gitee.com/mood1235/mapimg/raw/master/img/%E4%BB%A4%E7%89%8C03.png)

        + 创建的私人令牌需要复制到文档中记住，之后需要用到，一旦退出则无法复制令牌

一个令牌只能在一个PicGo上使用，如需在另一台PC上使用则需要在重新生成
一个新的令牌，同一个令牌不能同时使用

```
上传成功或者失败右下角会通知
特别注意：上传的图片的文件名不能和之前上传过的图片的文件名冲突，PicGo相册删除图片之后代码仓库的图片也会删除
```



## 转换成markdown格式的图床地址

+ 安装地址转换工具PicGo(安装包附带仓库中)

+ 设置PicGo

    + 下载扩展gitee-uploader 1.1.2 插件(需要下载Node.js否则则无法安装，安装包附带在仓库中)
    + Node.js需要安装到C盘，默认路径就可
    + 安装扩展插件之后![](https://gitee.com/mood1235/mapimg/raw/master/img/p02.png)

    + 设置仓库

        ![](https://gitee.com/mood1235/mapimg/raw/master/img/%E9%85%8D%E7%BD%AE01.png)

    ​	![](https://gitee.com/mood1235/mapimg/raw/master/img/%E9%85%8D%E7%BD%AE03.png)

![](https://gitee.com/mood1235/mapimg/raw/master/img/%E9%85%8D%E7%BD%AE02.png)



+ 将上述步骤执行完之后需要重启电脑使Node.js生效

+ 上传图片

    ![](https://gitee.com/mood1235/mapimg/raw/master/img/%E4%B8%8A%E4%BC%A000001.png)

![](https://gitee.com/mood1235/mapimg/raw/master/img/%E4%B8%8A%E4%BC%A0000002.png)



```
上传成功或者失败右下角会通知
特别注意：上传的图片的文件名不能和之前上传过的图片的文件名冲突，PicGo相册删除图片之后代码仓库的图片也会删除
```


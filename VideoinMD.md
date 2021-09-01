# 在 Markdown 中插入视频

## 插入 B 站视频

直接嵌入 B 站中已上传的视频，使用的是 B 站上的视频自带的视频播放器。

1. 在 B 站中，打开需要插入的视频，复制视频下方的“转发 > 嵌入代码”。

    ![20210901150739](https://raw.githubusercontent.com/WangXin008/ProductHelpDocumentation/main/20210901150739.png)

2. 在 markdown 中粘贴对应的代码，效果如下图所示。

    ```html
    <iframe src="//player.bilibili.com/player.html?aid=720018804&bvid=BV1qQ4y1Y7V2&cid=395043780&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"  width="700px" height="472px"> </iframe>

    ```

    ![20210901152028](https://raw.githubusercontent.com/WangXin008/ProductHelpDocumentation/main/20210901152028.png)

## 插入云上对象存储中的视频

直接插入本地已上传至公网的视频，使用的是自定义的 HTML 标签的视频播放器。

1. 将本地已有的 mp4 格式的视频文件上传至对象存储中，这里以阿里云的对象存储为例。

    ![20210901153523](https://raw.githubusercontent.com/WangXin008/ProductHelpDocumentation/main/images/20210901153523.png)

2. 在 markdown 中，编写如下 html 标签段，效果如下图所示。

    ```html
    <video controls height='100%' width='100%' src="https://encooacademy.oss-cn-shanghai.aliyuncs.com/activity/OpenBrowser.mp4"></video>

    ```

    > **说明：**
    >
    > 在 "src" 属性的值是变化的，需要更换对象存储中 mp4 视频的链接。

    ![20210901154520](https://raw.githubusercontent.com/WangXin008/ProductHelpDocumentation/main/images/20210901154520.png)

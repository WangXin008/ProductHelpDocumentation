# 技术文档 | 在 Markdown 中插入图片

## 概述

在写文档时，时常需要向文档中插入图片，以辅助用户理解。因此，图片也是可以很好地补充技术文档的文本。

图片与文字相结合，为用户提供更好的理解和记忆。特别是当用户快速浏览页面时，图片有助于用户更好地理解文档内容。其中，图片应该简单、具体，并强调明确的信息。

那么，如何在 Markdown 文件中插入图片呢？首先，需要明晰图片存储在哪里的问题，下面针对如下两种现象，展开说明其操作步骤。

- **当插入文档中的图片保存至 Github 文档仓库中的某个文件夹中时**

- **当插入文档中的图片保存至某对象存储中时**

## 图片存储至 Github 中

- **自定义图片名称**

1. 在写文档中需要用到的图片，需事先制作完成且定义好图片的名称，并保存于 Github 的文档仓库的某一文件夹中。

    ![20211015164753](https://raw.githubusercontent.com/WangXin008/ProductHelpDocumentation/main/images/20211015164753.png)

2. 使用 VSCode 工具，在 Markdown 文件中使用 Markdown 语法插入图片。

    ![20211015172542](https://raw.githubusercontent.com/WangXin008/ProductHelpDocumentation/main/images/20211015172542.png)

- **自动生成图片名称**

    使用 GitHub+PicGo 搭建图床的方式，自动生成图片名称，与在 Word 中直接粘贴图片的效果一样。

1. 在 VSCode 的扩展中，安装 PicGo 扩展。

    ![20211015174620](https://raw.githubusercontent.com/WangXin008/ProductHelpDocumentation/main/images/20211015174620.png)

2. 配置 PicGo 扩展，使之与 Github 中的文档仓库关联。

    ![20211015175538](https://raw.githubusercontent.com/WangXin008/ProductHelpDocumentation/main/images/20211015175538.png)

3. 复制本地电脑中的图片至剪贴板中。
4. 使用 VSCode 工具，在 Markdown 文件中需要插入图片的地方，使用快捷键 Ctrl+Alt+U 直接生成并粘贴已复制的图片。

    ![20211015180515](https://raw.githubusercontent.com/WangXin008/ProductHelpDocumentation/main/images/20211015180515.png)

## 图片存储至某对象存储中

1. 在写文档中需要用到的图片，需事先制作完成且定义好图片的名称，并保存于第三方对象存储的某一文件夹中。

    ![20211015173034](https://raw.githubusercontent.com/WangXin008/ProductHelpDocumentation/main/images/20211015173034.png)

2. 使用 VSCode 工具，在 Markdown 文件中使用 Markdown 语法插入图片。

    ![20211015174011](https://raw.githubusercontent.com/WangXin008/ProductHelpDocumentation/main/images/20211015174011.png)

## 写在后面

以上，仅个人在工作中使用小结，如果您还有其它更好的方式，欢迎给我留言讨论。

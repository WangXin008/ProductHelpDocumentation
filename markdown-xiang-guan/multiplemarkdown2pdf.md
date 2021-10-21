# 多个 Markdown 导出为 PDF

使用 gitbook 将多个 Markdown 导出为一本电子书的形式 PDF。

## 安装 NodeJS

在 windows 下安装 NodeJS，可参见 [安装步骤](https://www.jianshu.com/p/cc26e5d0f10f)。

## 安装 gitbook 工具

`npm install gitbook-cli -g`

> **说明：**
>
> gitbook-cli 是 GitBook 的一个命令行工具。它将自动安装所需版本的 GitBook 来构建一本书。

## 生成文档项目的目录结构

1. 将 gitbook 工具中的 `book.json` 文件拷贝至文档项目文件夹中。

    ![20210923102841](https://raw.githubusercontent.com/WangXin008/ProductHelpDocumentation/main/images/20210923102841.png)

2. 使用自行编写的脚本自动生成文档项目的目录结构。

    在脚本所在的路径下执行语句 `node summary_generate.js`

    ![20210923103810](https://raw.githubusercontent.com/WangXin008/ProductHelpDocumentation/main/images/20210923103810.png)

    ![20210923103956](https://raw.githubusercontent.com/WangXin008/ProductHelpDocumentation/main/images/20210923103956.png)

3. 在文档项目中自动生成了 `SUMMARY.md` 文件。

    ![20210923104616](https://raw.githubusercontent.com/WangXin008/ProductHelpDocumentation/main/images/20210923104616.png)

    > **说明：**
    >
    > 也可手动变更目录结构。

## 将多个 Markdown 生成 PDF 文档

1. 使用gitbook命令生成pdf。

    >**说明：**
    >
    >在使用`gitbook pdf`命令之前，通常需要使用`gitbook install`或`gitbook init`进行初始化。

    ![20210923105125](https://raw.githubusercontent.com/WangXin008/ProductHelpDocumentation/main/images/20210923105125.png)

2. 生成完成的pdf存放于文档项目中。

    ![20210923105607](https://raw.githubusercontent.com/WangXin008/ProductHelpDocumentation/main/images/20210923105607.png)

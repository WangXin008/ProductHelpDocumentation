# 统计多个 Markdown 文件的总字数

1. 打开需要统计字数的文档项目所在的文件夹目录。
2. 打开终端，此处使用的是git shell工具。

    ![20210929095430](/images/gitbashhere.png)

3. 在该终端中输入命令`find . -name '*.json' -exec cat {} \;|wc -m`，回车后等待统计的字数出现。

    ![20210929100644](/images/countword20210929.png)

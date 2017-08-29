# 新建第一个章节

项目新建好了，就开始新建第一个章节。

## 1. Add an article

点击 “TABLE OF CONTENTS” 面板中的 “Add an article” 按钮，输入章节名称。

![](/assets/add_article_new.jpg)

输入完成并点击 “Add” 按钮之后，即可以看到目录中已经出现了我们刚刚设置的章节了。

![](/assets/add_article_new_success.jpg)

再切换到 Files 面板中，可以看到有两点变化：

- 新增了一个文件 (gitbook.md)，注意左侧有个“绿条”的标记。
- 变更了一个文件（SUMMARY.md），注意左侧有个“黄条”的标记，修改的内容就是新增加了一行

![](/assets/add_article_files_change.jpg)

因为文件发生了变更，但是这些变更并没有提交，需要点击左上角的 “PUBLISH” 按钮，或者使用 `ctrl + s` 快捷键。

## 2. 添加内容

我们刚刚添加了“第一篇文章”，系统自动生成了 di-yi-pian-wen-zhang.md 文件。让我们在这里写上 `Hello, world!`。

> 你可以点击右下角的问号，找到 “Edit Markdown” 选项来开启编辑模式。
> 编辑完内容之后，一定要记得点击左上角的 “PUBLISH” 按钮。

## 3. Publish

完成 “Publish” 操作之后，我们回到项目首页 （https://www.gitbook.com/book/helinjiang/learn-gitbook/welcome），就可以看到 “Read” 按钮，点击之后就可以在线阅读了。

![](index_files/e12c1f12-1d72-498d-b85c-74f03b762766.png)

但是也可能会看到正在转化中的提示，此时请稍微耐心等待。

![](/assets/add_article_content_converting.jpg)


## 4. 冲突时需要手动同步（sync）到 GitHub 中

用户既可以在 GitBook 中编辑，也可以直接在 GitHub 中编辑，如果两个地方的数据有冲突（比如有移动、删除、修改之类的操作），则自动同步会失败，需要我们手动去确认同步的方式。

依然是进入 `SETTINGS - GitHub` 目录中，选择强制同步即可。

> 如此设置也是合理的，因为两个平台的数据毕竟不是存储在同一个地方，只是数据同步而已。冲突时，由用户选择如何合并解决冲突。

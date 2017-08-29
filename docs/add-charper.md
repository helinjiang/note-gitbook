# 新建章节

章节既可以平级，也可包含子章节。

## 1. 新建子章节

在 `TABLE OF CONTENTS` 中，在父章节上右键，选择 “Add Article”，填入章节名字之后，就成为了子章节。

例如我们在 `First Chapter` 下就新建了一个名字叫 “子章节” 的章节。

![](/assets/add_chapter_child.jpg)

同时，我们发现在 `SUMMARY.md` 文件中也有了新的变化：

![](/assets/add_chapter_child2.jpg)

## 2. 绑定子章节

第一步我们新建了子章节之后，发现它并不是超链接，因为它没有指向任何文件。

我们在 “子章节” 上右键，选择 “Edit Pointer”，发现它为空。我们可以填入任何超链接，比如 `http://www.qq.com`；也可以填写我们书籍的页面相对地址，比如 `xxx.md`。

填写完成保存之后，会发现 `SUMMARY.md` 更新了：

![](/assets/add_chapter_bind.jpg)

## 3. 手动操作

从上面的操作来看，我们可以手动修改 SUMMARY.md 文件的目录结构，效果是一样的。因此，完全可以不依赖这个平台来编辑，而可使用我们本地任意的工具来写。
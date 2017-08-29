# 使用 GitHub 来托管

默认情况下，文档托管在 GitBook 上，它也是基于 Git 的，例如我们的示例的 Git 地址就是 https://git.gitbook.com/helinjiang/learn-gitbook.git 。

但如果你想（习惯）使用 GitHub 的话，也是可以的。

## 1. GitHub 上新建仓库

首先需要在 GitHub 上新建一个仓库，仓库名字不一定要和 GitBook 上一致，比如，我们在 GitBook 上命名是 `learn-gitbook`，而在 GitHub 上命名为 `demo-learn-gitbook`。

## 2. 设置同步文件到 GitHub

在项目页中，选择 `SETTINGS - GitHub`，就可以看到 `Sync your content with GitHub` 页面。

![](/assets/use_github_bind.jpg)

点击“Select a Repository” 按钮，然后下拉选项里面选择仓库。最后点击 “Sync” 按钮即可。

![](/assets/use_github_sync.jpg)

> 我是使用 GitHub 帐号登录的 gitbook.com，如果你是用其他方式登录的 GitBook，可能此处的操作会有些不同，按提示操作即可。

## 3. 强制同步 force sync

上一步操作之后，有可能还不能够完成同步，因为可能存在文件冲突。用户需要自己选择是以 GitBook 的文件为主，还是以 GitHub 上面的文件为主。

> 这很正常，因为设置了同步，但很可能两边的文件都不一样，必定只能选择其中一个为主。另外，这一步的确认，也能够保证你万一误选择了另外一个仓库，而不至于将你的仓库中的内容删除干净了。

![](/assets/use_github_force_sync.jpg)

此处，我们选择的是 GitBook，点击之后，开始同步，最后显示状态。

![](/assets/use_github_sync_success.jpg)

## 4. 检查一下 GitHub 仓库

设置完成之后，我们在到 GitHub 中检查一下，发现内容果然都同步过来了。

![](/assets/use_github_sync_github_success.jpg)

## 5. 取消同步 unlink

如果你需要取消与 GitHub 的绑定，也是在这个页面中，可以选择不再同步。

![](/assets/use_github_unlink.jpg)

## 6. 其他

- [How can I transfer my content to GitHub?](https://help.gitbook.com/github/how-can-i-export-to-repo.html)
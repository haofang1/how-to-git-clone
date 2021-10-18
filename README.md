# how-to-git-clone
如果不懂怎么下载GitHub文件到自己电脑本地可以看这个教学

## 安装
在 Windows 上安装 Git 有多种安装方法，我选择在 Git 官方网站下载。 
打开  https://git-scm.com/download/win 下载会自动开始。 
**注意**这是一个名为 Git for Windows 的项目（也叫做 msysGit），和 Git 是分别独立的项目

详细安装教程参考https://www.cnblogs.com/hdlan/p/14395189.html

## 使用
可以建立一个新文件夹，在命令符中cd过去，输入git clone命令进行下载

注意，初次要求关联账户才能clone，选第二个选项后，在跳出的网页输入给的验证码后再输入账户密码即可关联
如果第一次关联失败，第二次下载可能显示fatal: destination path '.' already exists and is not an empty directory
将项目名的文件夹例图中的python_basic_grammar整个删除或者删除其中被隐藏的.git文件夹再git clone一遍即可

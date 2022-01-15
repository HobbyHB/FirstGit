# FirstGit
我的
Xcode与github结合使用详细教程

这是第一次在github提交学习资料，希望以后可以好好保持一个好的记录学习的习惯。
这是基于其他作者基础上的改良版教程。

主要是参考了现在网上的一些资料给没整过的人一个详细的指南。

（1）先在github上注册账号，自行解决喽。

（2）在导航栏右上角new一个repository（仓库）。

（3）填写仓库的名称、描述等信息。第二部是设置公开或者私人项目，隐私项目适合于公司的代码托管但是是收费的。

（4）下面就不用管了，在MAC电脑上生成你的ssh秘钥。

命令行操作后，然后在电脑打开任意文件夹上command+shift+g前往生成密钥的目录下：

（5）打开id_rsa.pub这个文件，将文件中的内容复制到github 》account setting 》SSH Keys 》Add SSH Key中

（6）点开项目将ssh的URL地址复制出来在客户端中就可以用了。

（7）新建项目，选择第二个。git@github.com:daleiwang/HelloProject.git

（8）将地址填入，然后将github上的这个项目的文件夹映射到本地的一个文件夹下。

（9）新建一个项目保存到本地的这个HelloProject下面。点击Source Controller 》 Commit。提交项目。

（10）点击Source Controller 》 Push

（11）最终项目已经提交到github上了。

这篇博客主要是参考了别人的博客加上自己的一点摸索。如果有问题希望指教！

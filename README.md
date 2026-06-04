# 这个仓库往GitHubPush镜像（https://github.com/Huliangyi/-gitcode-push）

这是添加镜像同步后第1次提交commit，时间：11:24

这是添加镜像同步后第2次提交commit，时间：11:28

----
不好意思，刚刚11:28不小心点了手动同步，手动同步5分钟是对的，同步成功。

但是现在要验证的是CD期间内自动同步的功能

----

这是添加镜像同步后第3次提交commit，时间：11:30，在CD时间内，看这条会不会同步

这是添加镜像同步后第4次提交commit，时间：11:31，在CD时间内，看这条会不会同步

这是添加镜像同步后第5次提交commit，时间：11:31，在CD时间内，看这条会不会同步

-----

结论：CD期间内的commit，没有同步，如下图：
![image.png](https://raw.gitcode.com/user-images/assets/10033296/03e9befb-2559-477a-98aa-ca662a39523f/image.png 'image.png')

如果我这条commit提交了，还是没有自动触发同步，则CD外自动同步功能也坏了，时间：17:24

-----
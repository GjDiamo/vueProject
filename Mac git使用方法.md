Mac 在与GitHub 交互的时候稍微和windows 有些不同。

mac  创远程库时的ignore文件会显示不出来，这个Mac系统出于安全考虑的内置；

解决办法：在远程仓库创建的时候直接创建仓即可（Redeme?怎么办）

1. gitHub -》 New repositroy -》 复制地址；
2. 开启终端 找到对应文件（如下图）

![屏幕快照 2018-07-13 下午12.49.16](/Users/guohaijiao/Desktop/MacgitHub/屏幕快照 2018-07-13 下午12.49.16.png)

​       cd 后可以直接拖想要上传的文件夹；

​       pwd:当前工作目录的完整路径

​       ls : 查看本文件内容；

​       ls -a：是指即可看到本机隐藏文件；

​       git init:生成本地仓库；

​       git status：查看状态；

​       Touch .gitignore ：创建ignore文件

​       mkdir ：创建文件

​       vim .gitignore:进入.gitignore内进行添加忽略文件；

​        i：插入；

​        XXX文件，

​        esc ：结束

​        shift+: +wq  (保存退出)

​        shift+: +q！  (退出)     

​        Wq:保存并退出；    

​       git add --all:添加致购物车；

​       git commit -m "add gitignore" 

​       git remote add origin git@github.com:GjDiamo/test.git ：链接远程仓库；

​       git push -u origin master  ：上传就OK
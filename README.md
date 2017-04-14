git 仓库的主要步骤
1、下载git并成功安装。
2、打开git bash 
  首先配置自己的身份，这样在提交代码的时候就能知道是谁提交的
   git config --global user.name "名字"
   git config --global user.email "邮箱地址"

   注意：用户名、邮箱和github上的一致

3、在github新建仓库  在本地进行clone
4、git push origin master的时候会报错

   那是因为本地和远端没有建立连接

   通过一个命令完全搞定  git config receive.denyCurrentBranch ignore
5、下边可以进行项目开发了  


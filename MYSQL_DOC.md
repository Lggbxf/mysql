## 20170614
>安装git并会基本的使用
1. 创建版本库
- 第一步, 先要创建一个目录, 这个目录就是用来存放仓库的:mkdir html;cd html
- 第二步, 使用git init命令, 将当前目录创建成git仓库:git init
- 增加文件:touch README
- 编辑这个文件, 写一点东西在里面:vim README
- 先用查看当前状态的命令, 查看一下现在目录下文件的状态:git status
-把文件加到仓库中去, 只有加到仓库中了, 才可能看一下文件的变化:git add README
-现在使用查看状态的命令, 看一下是目录下文件的状态:git status
-提交:git commit
- 配置用户信息:git config --global user.name;git config --global user.email;git config --global core.editor vim
- 查看提交信息:git log
## 20170615
>git远程仓库
1. 添加远程仓库：git remote add origin https://github.com/wangleihd/h5class.git
2. 远程的仓库的信息更步到本地：git fetch origin
3. 同步master分支：git push origin master
4. 同步其它分支：git push origin branch-name
>安装并使用mysql
1. 创建数据库：create database <数据库名>
2. 显示数据库：show databases;
3. 删除数据库：drop database <数据库名>
4. 使用数据库：use <数据库名>
5. 创建数据表：create table <表名>
6. 表结构：desc 表名
7. 删除表:drop table <表名>
8. 查询表中的数据: select <字段1，字段2，...> from < 表名 > where < 表达式 >
9. 修改表中数据:update 表名 set 字段=新值,... where 条件
10. 增加字段:alter table 表名 add字段 类型

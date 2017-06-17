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

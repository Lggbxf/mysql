# 学生信息管理系统

# 数据库设计方案
## 学生信息表设计

| 中文名称 | 表名 | 字段属性 | 默认值 | 备注 |
|---------|------|--------|-------|------|
| 学号 | sno | int（10）| 必填 | 主键 |
| 姓名 | name | char(10)| 必填 | 主键 |
| 性别 | sex | char(4) | 必填 | 无 |
| 系号 | deptno | char(10) | 必填 | 外键 |
| 标志位 | flag | int(3) | 必填 | 0 |

## 学校设计表设计
| 中文名称 | 表名 | 字段属性 | 默认值 | 备注 |
|---------|-----|---------|-------|------|
| 系编号 | deptno | int(10) | 必填 | 主键 |
| 学校名 | schoolname | char(20) | 必填 | 无 |
| 系名 | dept | char(20) | 必填 | 外键 |

## 学生成绩表设计
| 中文名称 | 表名 | 字段属性 | 默认值 | 备注 |
|---------|-----|---------|-------|------|
| 学号 | sno | int(10) | 必填 | 外键 |
| 姓名 | name | char(10) | 必填 | 外键 |
| 课程名 | class | char(10) | 必填 | 无 |
| 分数 | score | int(2) | 必填 | 无 |
| 标志位 | flag | int(3) | 必填 | 0 |
# CGI程序设计接口
```sql
 create table information(
   sno int(10) primary key,
   name varchar(10) not null,
   sex varchar(4) not null,
   deptno varchar(10) not null,
   flag int(3) not null
 )default charset=utf8;
 ```
 
 ```sql
 create table school(
   deptno int(10) primary key,
   schoolname varchar(10) not null,
   dept varchar(10) not null
 )default charset=utf8;
 ```
 
 ```sql
 create table information(
   sno int(10) not null,
   class varchar(10) not null,
   score int(10) not null,
   flag int(3) not null
 )default charset=utf8;
 ```

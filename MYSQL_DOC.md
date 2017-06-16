# 我的数据库日记
## 20170612
安装linux
>熟悉一些常用的基本命令
1. 文件的创建、删除、复制、重命名、移动:touch  file;cp file file1;cp file  /home/linux/file1;mv file file2;mv file  /home/linux/
2. 列出文件列表:ls -al  .
3. 查看文件内容:cat  file
4. 目录的创建、删除、复制、重命名、移动:mkdir dir;cp dir   dir1  -a;cp dir   /home/linux/dir2  -a;mv dir  dir2;;mv dir  /home/linux/;rm  dir  -rf
5. 列出目录列表:ls -d  dir
6. 目录中查找文件:find  ./dir  -name  "filename"
7. 使用gzip和gunzip对文件进行压缩和解压缩:gzip  filename;gunzip filename
8. 使用bzip2和bunzip2对文件进行压缩和解压缩:bzip2  filename;bunzip2  filename
9. 使用tar对文件和目录进行压缩和解压缩:tar czvf  file.tar.gz dir;tar cjvf  file.tar.bz2 dir;tar cJvf  file.tar.xz  dir;tar xvf  file.tar.gz;tar xvf  file.tar.xz
## 20170613
>学习使用vi和vim
1. i：在当前字符的左边插入
2. I：在当前行首插入
3. a：在当前字符的右边插入
4. A：在当前行尾插入
5. o：在当前行下面插入一个新行
6. O：在当前行上面插入一个新
7. h: 向前移动一个字符
9. j: 向上移动一行
10. k: 向下移动一行
11. l: 向后移动一个字符
12. yy: 复制当前一行
13. dd:剪切当前一行
14. p: 粘贴内容到游标之后
15. P: 粘贴内容到游标之前

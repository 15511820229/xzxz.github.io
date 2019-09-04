Title: 解决阿里云出现-bash-4.2
Date: 2017-11-10 10:20
Modified: 2017-11-10 19:30
Category: 技术
Tags: pelican, publishing
Slug: my-super-post1
Authors: 董懂

阿里云路径原本显示：root@主机名+路径不知为什么变成了-bash-4.2

解决方法：cp /etc/skel/.bashrc /root/
         cp /etc/skel/.bash_profile  /root/

关闭，再次登陆
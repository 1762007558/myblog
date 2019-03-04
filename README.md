```bash
# 创建文件夹
mkdir myblog
# 创建项目
django-admin startproject main myblog
# 进入项目目录
cd myblog
# 数据迁移(创建、修改数据库表)
python manage.py migrate
# 创建超级管理员账户(admin/yz@1212112)
python manage.py createsuperuser
# 启动Web服务器
python manage.py runserver 127.0.0.1:8282
```
```bash
# 初始化
git init
# 状态
git status
# 添加
git add ...
# 提交
git commit -m "first commit"
# 日志
git log
# 添加远程用户
git remote add origin https://github.com/1762007558/myblog.git
# 推
git push -u origin master
```
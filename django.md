### 安装python3.4.x
### 使用虚拟环境Virtualenv
`pip install virtualenv`
`virtualenv 目录\虚拟环境名称`
### 安装Django 1.11
pip install Django==1.11
> 创建项目
`django-admin startproject xiangmu`
`python -m django --verssion`查看版本
> 开发服务器
`python manage.py runserver`

> settings.py 内容设置
LANGUAGE_CODE= 'zh-hans'
TIME_ZONE='Asia/Shanghai'

> 创建应用
`python manage.py startapp yingyong`

'settings.py增加应用'
INSTALLED_APPS 下面增加应用 'yingyong',

> 在数据库中创建表
python manage.py migrate

创建一个管理用户
python manage.py createsuperuser


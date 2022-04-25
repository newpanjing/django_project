# Django SimplePro项目模板

这是一个django+simplepro的模板，可以用来快速开发一个项目。

## 使用说明

### 数据库配置

本示例默认使用`sqlite3`，如果你想使用`mysql`或者其他数据，请在`settings.py`中修改。然后在进行以下的步骤。

### 安装依赖

```shell
pip install -r requirements.txt
```

### 执行迁移

这一步骤是为了让`Django`框架自动创建表结构和生成一些基本的数据

```shell
python manage.py makemigrations
python manage.py migrate
```

### 创建管理员

先执行以下的命令，然后按照提示输入管理员信息。

```shell
python manage.py createsuperuser
```

### 启动访问

默认的情况下，访问地址是：`http://127.0.0.1:8000/admin`，输入在上一步中创建的管理呀和密码即可。

```shell
python manage.py runserver
```

## 提示

✅完成以上步骤，你就能访问一个基于`Django`+`SimplePro`的项目了，
这是和打开任意的`admin`页面，将会提示激活`SimplePro`框架，可以去[官网购买](https://simpleui.72wo.com/simplepro#buy)激活码。

## QQ群
如果你在使用过程中遇到任何问题，可以加入QQ群和大家一起交流探讨。
> 群号：722755389
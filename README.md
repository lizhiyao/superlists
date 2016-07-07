# 创建项目

    django-admin.py startproject superlists

# 创建一个应用

    python manage.py startapp lists

# 目录说明

```
superlists                   保存应用于整个项目的文件
    settings.py              存储网站的全局配置信息
lists                        lists应用

```

# 相关知识

1. 功能测试站在用户的角度从外部测试应用，单元测试则站在程序员的角度从内部测试应用。

2. Django遵守了经典的“模型-视图-控制器”（Model-View-Controller，MVC）模式，但并没严格遵守。
Django确实有模型，但视图更像是控制器，模板其实才是视图。不过，MVC的思想还在。

3. Django和任何一种Web服务器一样，其主要任务是决定用户访问网站中的某个URL时做些什么。


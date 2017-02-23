laravel5.4基础框架
=================

## 目的

不需要重复配置

## 添加内容

1.增加一个listen监听sql查询打印日志

2.增加laravel ide helper

3.增加McLibs目录，McLibs\functions\helpers.php添加通用方法

4.增加[laravel-debugbar](https://github.com/barryvdh/laravel-debugbar)

5.增加自定义异常处理

6.修改默认时区为Asia/Shanghai

## 使用

```
git clone https://github.com/kailian/base-laravel.git

composer install

cp .env.example .env
```

## 配置说明

vi .env

```
APP_DEBUG=false  //生产环境使用自定义404页面

DEBUGBAR_ENABLE=true  //开启debugbar
```
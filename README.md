# 后台配置系统

## 安装
* composer require wubuze/backend-system

- config/app.php 文件中provider 加上

* Wubuze\BackendSystem\LaravelServiceProvider::class,

*   php artisan vendor:publish


## 迁移数据库,创建model

- php artisan migrate 生成表 system


# system 模块

## 安装

- make:system


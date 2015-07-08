#博客系统

#### 2015-07-8
使用laravel 5 LTS 进行开发

### 安装说明

数据库，并修改 `.env` 配置文件：

请根据数据库与服务器实际情况修改 `.env` 配置文件，这里给出一个示例。

```php
APP_ENV=local
APP_DEBUG=true
APP_KEY=RrQvzbUxaKIlj74s3hOYClGQ71zoVixr

DB_HOST=localhost
DB_DATABASE=blog
DB_USERNAME=root
DB_PASSWORD=root

CACHE_DRIVER=file
SESSION_DRIVER=file
QUEUE_DRIVER=sync

MAIL_DRIVER=smtp
MAIL_HOST=blog.fanshub.org
MAIL_PORT=2525
MAIL_USERNAME=null
MAIL_PASSWORD=null



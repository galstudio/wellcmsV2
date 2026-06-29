### Introduction
WellCMS 3.0 — это система управления контентом для высоконагруженного сайта, построенная на современной архитектуре PHP, поддерживающая расширения плагинов, настройку тем, сегментирование базы данных и планирование задач.

### Key Features
- **Modern PHP Architecture**: PSR-7 HTTP standard, dependency injection container, and service provider pattern
- **Plugin System**: Install, uninstall, enable plugins, and connect to the plugin market
- **Theme Mechanism**: Parent-child theme inheritance and custom templates
- **Database Capabilities**: Connection pooling, read/write splitting, sharding, and partition maintenance
- **Task Scheduling**: Built-in scheduler supporting cron jobs and queue execution
- **Multi-language Support**: 14 built-in language packs
- **Caching System**: Redis, Memcached, APCu, Yac, and more cache drivers
- **Security Management**: CSRF, XSS, permissions, tokens, IP blacklist, and more
- **Swoole Support**: Swoole Server and coroutine runtime support

### Installation
1. Deploy the code to your web root directory
2. Copy `src/Config/*.default.php` to `config/*.php` and configure as needed
3. Visit `/install/` to complete database installation

### Requirements
- PHP >= 8.0
- MySQL / MariaDB / PostgreSQL / SQLite
- Redis (optional, for caching and task queues)

### Notes
- This is the first release, recommended for testing and evaluation environments
- For production deployment, please read `bin/SWOOLE_DEPLOY_GUIDE.md` and `bin/SCHEDULER_DEPLOY_GUIDE.md` first

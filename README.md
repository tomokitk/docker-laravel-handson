# [docker-laravel-handson](https://qiita.com/ucan-lab/items/56c9dc3cf2e6762672f4#github%E3%81%8B%E3%82%89%E3%83%AA%E3%83%9D%E3%82%B8%E3%83%88%E3%83%AA%E3%82%92%E3%82%AF%E3%83%AD%E3%83%BC%E3%83%B3)を参考に作成

# ログイン認証
Laravel Breezeを使用

# 手順
クローン
docker compose exec app bash
chmod -R 777 storage bootstrap/cache
composer install
cp .env.example .env
php artisan key:generate
php artisan storage:link
npm install
npm run build

http://localhost:8080/



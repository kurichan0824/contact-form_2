# contact-form_2

# お問い合わせフォーム

## プロジェクト概要
Laravelを使用したお問い合わせ管理システム

## 使用技術
- Laravel 8.x
- PHP 8.1
- MySQL
- Docker

## 実装機能
- お問い合わせフォーム入力
- バリデーション処理
- 確認画面表示
- データベース保存
- 管理画面（検索・一覧表示）

## 環境構築
```bash
docker-compose up -d
docker-compose exec php bash
composer install
php artisan migrate --seed
php artisan serve
アクセス方法
お問い合わせフォーム: http://localhost:8000

管理画面: http://localhost:8000/admin

# docker-laravel-handson

## 参考サイト
https://qiita.com/ucan-lab/items/56c9dc3cf2e6762672f4

## クローン後

#### ビルド
```
docker-compose up -d --build
```

#### コンテナに入る
```
docker-compose exec app bash
```

#### Conposerをインストール
```
composer install
```

#### .envを作る
```
cp .env.example .env
```

#### アプリケーションキーを作成
```
php artisan key:generate
```

#### マイグレート
```
php artisan migrate
```
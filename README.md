## Dockerを一切使わずにシンプルにLaravelを触るための一連の手順メモ
1. [laravel/laravel](https://github.com/laravel/laravel)をフォーク
2. [imo-tikuwa/laravel](https://github.com/imo-tikuwa/laravel)のSettingsでTemplate repositoryのチェックを入れる
   - フォークしたリポジトリがテンプレートリポジトリとして使用できるようになる
3. テンプレートを元にリポジトリを作成（当リポジトリ）
4. ローカルにクローン
5. cp .env.example .env
6. composer install
7. npm install
8. php artisan key:generate
9. php artisan serve

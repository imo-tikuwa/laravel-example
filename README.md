## Dockerを一切使わずにシンプルにLaravelを触るための一連の手順メモ
1. [laravel/laravel](https://github.com/laravel/laravel)をフォーク
2. [imo-tikuwa/laravel](https://github.com/imo-tikuwa/laravel)のSettingsでTemplate repositoryのチェックを入れる
   - フォークしたリポジトリがテンプレートリポジトリとして使用できるようになる
3. テンプレートを元にリポジトリを作成（当リポジトリ）
4. ローカルにクローン
5. composer install、npm install実行
6. APPキー作成（php artisan key:generate）
7. php artisan serve実行

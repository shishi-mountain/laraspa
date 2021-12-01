## Laravel+Vue.js+nginx環境構築
laravel,npm,vue.js,mysql
### 参考URL
https://yutaro-blog.net/2021/05/25/docker-laravel-vuejs-m1/

https://yutaro-blog.net/2021/04/28/docker-laravel-vuejs-1/
### 特別に対応したこと
- nginx 　でポートエラー　81を利用に変更
- file sharingのエラー　itermにて大文字小文字を気にするとOK

- ブラウザ接続
localhost:82

ローカル
Documents/docker/laraspa/


## Laravel 6 APIとVue.jsでSPA構築 最速入門
### 参考URL
https://noumenon-th.net/programming/2020/02/13/laravel-vue-spa/

### エラー対応
- composer require laravel/uiでエラー
```
composer require laravel/ui:1*
```
https://zakkuri.life/%E3%80%90laravel%E3%80%91composer-require-laravel-ui%E3%81%A7%E3%82%A8%E3%83%A9%E3%83%BC/

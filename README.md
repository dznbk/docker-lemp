# docker-lemp
nginx,php,mysqlの簡易環境構築します。

## 動作確認環境
WSL2にて確認済。  
WSL2の有効化については[qiitaに記事をあげています](https://qiita.com/D-PONTARO/items/b2fc28ab68d694646e0f)ので参考までに。

## 起動手順
### 環境変数の設定
.env.example -> .env を複製し、各変数を設定ください。

### ビルド 
```bash
docker-compose build
```

成功すると、"Successfully built…"というメッセージが表示されます。

### 起動
```bash
docker-compose up -d
```

### 参考サイト
[こちらのブログ](https://yutaro-blog.net/2021/04/28/docker-laravel-vuejs-1/)を参考にしました。  
上記ブログではLaravel,vueが含まれていますが、当リポジトリには含めずLEMPまでに留めています。

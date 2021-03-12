# 簡易ブログアプリ
オススメのご飯屋さんのメニューを紹介する簡易ブログアプリです。

### 実装されてる機能の一覧

- deviceを使ったユーザー管理とログイン・ログアウト機能
- ブログ機能
- コメント機能
- お気に入り機能
- 検索機能
- 画像アップロード機能
- フォロー機能
- カテゴリー(タグ)機能
- 多言語化対応
- ページネーション
- Rspecを使ったテスト
- CircleCIによる自動テスト

### ローカルで動かす
GitHubからpullしてきたらプロジェクトフォルダに移動して、`./qs init --webpack`してください。

```
$ git clone https://github.com/belion-freee/sample_restraunt_blog.git <Project name>
$ cd <Project name>
$ ./qs init --webpack
```

`http://localhost:3000`にアクセスするとアプリが利用可能です。

以降の開発では `./qs server` でアプリを起動してください。

seedで初期アカウントを登録してるので、すぐに動作確認できます。
```
# You can use those accounts

name: "hoge"
email: "hoge@sample.com"
password: "Password"

name: "foo"
email: "foo@sample.com"
password: "Password"
```

- ログイン・ログアウト機能
![douga1](https://user-images.githubusercontent.com/69951545/110927918-96d0c080-8369-11eb-87a7-6b71a7a27ae3.gif)

- ページネーション機能
![douga22](https://user-images.githubusercontent.com/69951545/110968981-82a5b700-839b-11eb-9a0f-c241b447e0e4.gif)

- 検索機能
![douga32](https://user-images.githubusercontent.com/69951545/110969970-a0275080-839c-11eb-8810-5b52a2efe94c.gif)

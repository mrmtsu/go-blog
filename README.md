# 行いたいこと
技術Blogを作る

# 詳細
●管理者のみ投稿・投稿更新・投稿削除を行える<br>
●管理者以外はユーザ登録の上、閲覧のみ<br>
●投稿の登録や更新・削除などに対してのみJWT認証を要求する<br>

# エンドポイント
|  URL  |  ページ  |
| ---- | ---- |
|  /  |  トップページ  |
|  /api/user/register  |  ユーザ登録  |
|  /api/user/login  |  ログイン  |
|  /api/user/logout  |  ログアウト  |
|  /api/article/create  |  投稿  |
|  /api/article/put  |  投稿更新  |
|  /api/article/delete/:id  |  投稿削除  |
|  /api/articles/list  |  投稿一覧  |
|  /api/articles/list/:id  |  投稿詳細  |

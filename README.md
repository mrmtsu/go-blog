# 行いたいこと
技術Blogを作る

# 詳細
●管理者のみ投稿・投稿更新・投稿削除を行える<br>
●管理者以外は閲覧のみ（投稿詳細を見る場合はユーザ登録が必要）<br>
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

# ER図
![image](https://user-images.githubusercontent.com/60598010/112742568-a3405480-8fca-11eb-85c1-58e50dda108b.png)

# SNS　clone App

## Backend

DjangoRestFramework & JWT 認証

## Frontend

```bash
React Hooks & Redux Toolkit
Typescript & Material UI
Formik + Yup
```

## 機能

```bash
email & password アクセス
プロフィール編集機能
投稿機能
いいね機能
コメント機能
```

## database

User

```bash
id
email
password
```

Profile

```bash
id
nickname
userProfile
img
created_at
```

Post

```bash
id
title
userPost
img
liked
created_at
```

Profile

```bash
id
text
userComment
post
```

## API Endpoint

```bash
api/register/      [POST]  新規アカウント作成
api/myprofile/     [GET]  ログインユーザーのProfile取得
api/comment/       [GET/POST]  コメントの取得と投稿
api/post/          [GET/POST/PUT/PATCH]  投稿の取得、作成、更新、一部更新
api/profile/       [GET/POST/PUT]  Profileの取得、作成、更新
authen/jwt/create/ [POST]  JWTトークン取得
```

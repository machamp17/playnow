# PLAY BRANDING

PLAY BRANDING（by 株式会社WITH HOLDINGS）のランディングページ。

## ファイル構成

```
/
├── index.html          デバイス判定（自動でPC/モバイル版に振り分け）
├── desktop.html        PC版ランディング
├── legal.html          会社概要・特商法・プライバシーポリシー
├── mobile/
│   └── index.html      モバイル版ランディング
└── assets/             画像素材
```

## ローカルで確認する

`index.html` をブラウザで開くだけ。

## GitHub Pagesで公開する

1. このリポジトリを GitHub にプッシュ
2. `Settings` → `Pages` → `Branch: main` / `Folder: / (root)` を選んで Save
3. 数十秒後に `https://<ユーザー名>.github.io/play-branding/` で公開されます

独自ドメインに切り替える場合は、`Settings` → `Pages` → `Custom domain` にドメインを入力し、DNS の CNAME を `<ユーザー名>.github.io` に向ければOK。

# HALE MAKAWAO Website

ハレマカワオ（HALE MAKAWAO）公式サイトのソースコード。

- 本番URL: https://halemakawao.com/
- ホスティング: GitHub Pages
- 言語版: 日本語（ルート）/ English (`/en/`) / 中文 (`/zh/`)

## 構成

静的HTMLサイト（CSS/JSはインライン）。

```
.
├── index.html       # 日本語トップ
├── stay.html        # 宿泊案内
├── food.html        # お食事
├── access.html      # アクセス
├── news.html        # お知らせ
├── en/index.html    # English version
├── zh/index.html    # 中文版
├── images/          # 画像（webp/jpg）
├── robots.txt
├── sitemap.xml
└── CNAME            # GitHub Pages 用カスタムドメイン
```

## 編集・公開フロー

1. ローカルで HTML を編集
2. `git add . && git commit -m "<変更内容>"`
3. `git push origin main`
4. GitHub Pages が自動デプロイ（数分以内に反映）

## ローカル動作確認

```bash
python3 -m http.server 8000
# ブラウザで http://localhost:8000/ を開く
```

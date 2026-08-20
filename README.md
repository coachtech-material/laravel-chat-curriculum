# COACHTECH × PHP / Laravel 入門

プログラミングがはじめての方が、ブラウザだけで自分のチャットアプリをつくりあげる入門教材です。

公開サイト: https://coachtech-material.github.io/laravel-chat-curriculum/

## 構成

| 場所 | 内容 |
|---|---|
| `curriculums/` | 教材本体（Part > Chapter > Section） |
| `assets/` | 画面キャプチャと概念図 |
| `docs/index.md` | 公開サイトのトップページ |
| `docs/stylesheets/custom.css` | 配色とレイアウト |
| `scripts/build_docs.py` | `curriculums/` を英語スラッグの `docs/` に変換する |

## ローカルで確認する

```bash
pip install -r requirements.txt
python3 scripts/build_docs.py
python3 -m mkdocs serve
```

`main` への push で GitHub Actions が自動デプロイします。

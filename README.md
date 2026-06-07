# posse-towerbattle

ブラウザ上で動く静的なタワーバトルゲームです。

## Local preview

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open http://127.0.0.1:8000/.

## Vercel deployment

このリポジトリはフロントエンドのみの静的サイトです。Vercel では次の設定で公開できます。

- Framework Preset: Other
- Root Directory: `.`
- Build Command: 空欄
- Output Directory: `.`
- Install Command: 空欄
- Production Branch: `main`

GitHub 連携で `main` に push すると、その内容が本番デプロイ対象になります。

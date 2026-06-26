# App Store 申請用ファイル

- `app-store-listing.md` — App Store Connect にコピペするメタデータ一式（説明文・キーワード・審査メモ等）
- `privacy-policy.html` — そのままホスティングできるプライバシーポリシー

## プライバシーポリシーの公開（GitHub Pages が最速・無料）

1. GitHub にリポジトリを用意（既存の danceformula でも可）
2. `privacy-policy.html` をリポジトリに置く（例：`docs/privacy-policy.html`）
3. リポジトリ Settings → Pages → Source を `main` / `docs` フォルダに設定
4. 数分後に公開される URL を App Store Connect の「プライバシーポリシー URL」に入力
   - 例：`https://<ユーザー名>.github.io/danceformula/privacy-policy.html`

> GitHub を使わない場合は、Netlify Drop（ドラッグ&ドロップ）、Vercel、
> Cloudflare Pages などでも HTML 1枚を数分で公開できます。

## メール連絡先の差し替え

`privacy-policy.html` と `app-store-listing.md` の連絡先メール（現在
`yidev41@gmail.com`）は、公開用に使いたいアドレスへ変更してください。

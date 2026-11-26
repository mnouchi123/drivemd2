# DriveMD2 Frontend

GitHub Pages 用の静的フロントエンドです。

## Current Features

- `Obsidian_Vault` 配下のフォルダ一覧表示
- Markdown ファイルのプレビュー表示
- Markdown ファイルの編集と保存
- 現在フォルダ配下への新規 `.md` 作成
- ブックマーク
- テーマ切替
- フォントサイズ調整
- 目次表示
- プレビュー画面での `ALL` ボタンによる全文コピー
- API キー認証（設定画面で入力、端末の localStorage に保存）
- Obsidian_Vault より上の仮想最上位フォルダ（backend で `EXTRA_ROOT_FOLDERS` 設定時）

## Default Backend

- `https://drivemd2-proxy-6lgmhmjk7a-an.a.run.app`

## Override

設定画面から `API Base URL` と `API キー` を変更できます。  
または `?apiBaseUrl=https://...` のクエリでも上書きできます。

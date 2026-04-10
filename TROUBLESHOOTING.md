# TROUBLESHOOTING

V-Forge の配布版や開発中に起きやすい問題を、先に切り分けるための簡易ガイドです。

## まず確認すること

- 最新の `RELEASE_GUIDE.md` を確認する
- `USER_QUICK_START.md` の手順を上からやり直す
- アプリを再起動して、サンプルデータや古い設定が原因でないか見る

## SmartScreen で止まる

1. 「詳細情報」をクリックする
2. 発行元が GitHub Releases の配布物か確認する
3. 「実行」をクリックする
4. 迷ったら `USER_QUICK_START.md` の SmartScreen 手順を確認する

配布元が不明な場合は実行しないでください。恒久対策としてはコード署名の導入を検討します。

## ZIP や実行ファイルが警告される

- 配布物は公式 Release のものか確認する
- ZIP の展開後にファイルが欠けていないか確認する
- ソース公開済みであることを案内する

## ブラウザ版で動作確認したい

- `npm run dev` でブラウザ版を起動する
- Tauri 版の確認は `npm run tauri dev` を使う
- ブラウザ版では使えない機能があるため、デスクトップ版との差分を把握する

## OBS 連携がうまくいかない

- Browser Source URL を再コピーする
- OBS 側のキャッシュを更新する
- `src-tauri` 側のローカルサーバーが起動しているか確認する

## 直らないとき

- 再現手順、スクリーンショット、実行したバージョン番号をそろえて `https://github.com/ChildrensLimbo/v-forge-releases/issues` にまとめる
- どの画面、どの機能、どの環境で起きたかを一緒に残す

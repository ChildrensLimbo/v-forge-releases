# V-Forge クイックスタート

public 配布リポジトリの GitHub Releases から配布版を入手して、そのまま起動するための案内です。

## まずはここから

- **YouTube API の設定がなくても**、コメント画面のサンプル表示から動きを確認できます
- 初回はホームの **「はじめてのセットアップ」** を上から進めると、迷いにくいです
- ミニサイトを公開したい場合は、先に `docs/MINISITE_DEPLOY_GUIDE.md` を見ておくと流れがつかめます

## ダウンロード

1. GitHub Releases を開く
2. Windows は `V-Forge_<version>_x64-setup.exe` を優先して選ぶ
3. もう一つの Windows 版が必要な場合は `V-Forge_<version>_x64_ja-JP.msi` を使う
4. 初回起動時に SmartScreen の警告が出る場合があります

## 初回セットアップの流れ

1. アプリを起動したら、ホーム画面の案内に沿って最初の 1 件のスケジュールを入れる
2. コメント画面でサンプルを開いて、表示や操作感を先に確認する
3. OBS に Browser Source URL を貼って、配信画面への映り方を確認する
4. 必要になったタイミングで YouTube API の設定を進める

YouTube API の設定前でも、サンプル表示だけで画面の使い方は確認できます。

## 初回起動で迷いやすい点

- **GitHub アカウントは不要** です
- **SmartScreen が出たら**:
  1. 「詳細情報」をクリック
  2. 発行元が GitHub Releases の配布物か確認
  3. 「実行」を押す
- **詳細情報 → 実行** は、配布元を確認したうえで進めてください
- macOS と Linux の配布物は Release ページの説明に従って選んでください
- 不具合報告は `https://github.com/ChildrensLimbo/v-forge-releases/issues` にまとめてください

## 困ったとき

- どのファイルを選ぶか分からないときは、まず Windows の `-setup.exe` を選んでください
- 起動できない場合は、配布ページの説明と `RELEASE_GUIDE.md` を確認してください
- コメント画面の動きだけ先に見たいときは、サンプル表示から試してください
- 不具合報告は `https://github.com/ChildrensLimbo/v-forge-releases/issues` に統一してください


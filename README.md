# Streamer Launch Box

Streamer Launch BoxはTwitch配信向けのデスクトップアプリです。

## Windows 正式版

[最新版のインストーラーはこちら](https://github.com/UtahArts/StreamerLaunchBox-Releases/releases/latest)

- 対象：Windows 10 / 11 x64
- `StreamerLaunchBox-Setup-*.exe`：本体。基本ガチャを同梱しています。
- `SHA256SUMS.txt`：配布ファイルの照合用ハッシュ。

.NET実行環境を同梱しています。WebView2など別の依存要件は、Windows環境によって準備が必要です。

## macOS 試作版

[macOS試作版 v0.1.0 のダウンロード](https://github.com/UtahArts/StreamerLaunchBox-Releases/releases/tag/mac-preview-v0.1.0)

- 対象は macOS 14 以降。Apple Silicon（Mシリーズ）用とIntel Mac用のZIPを用意しています。
- プリセットに登録したアプリ・フォルダー・Webページを一括で開けます。
- **実機動作テスト未実施。** AppleのDeveloper ID署名と公証も未実施です。

## Windowsアプリの更新

0.2.41以降は、アプリの「情報 → アプリの更新」からGitHub Releasesの正式版を確認できます。GitHubへのログインは不要です。

0.2.40以前は従来の配布サイトから移行版0.2.41へ更新できます。その後はGitHub Releasesを使用します。

## このリポジトリについて

このリポジトリはインストーラーと配布説明の公開専用です。アプリケーションの実装ソースは非公開で、ここには含めていません。

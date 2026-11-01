# Streamer Launch Box

Twitch配信向けのWindowsデスクトップアプリです。

## ダウンロード

[最新版のインストーラーはこちら](https://github.com/UtahArts/StreamerLaunchBox-Releases/releases/latest)

- 対象：Windows 10 / 11 x64
- `StreamerLaunchBox-Setup-*.exe`：本体。基本ガチャを同梱しています。
- `GachaManager-Setup-*.exe`：基本ガチャの個別インストーラー。本体を導入する場合、通常は不要です。
- `LaunchBoxSlot` / `LaunchBoxRoulette` / `LaunchBoxPrizeRoulette` / `LaunchBoxPachinko` / `LaunchBoxTrainVote`：追加ゲームの個別インストーラー。
- `SHA256SUMS.txt`：配布ファイルの照合用ハッシュ。

.NET実行環境を同梱しています。WebView2など別の依存要件は、Windows環境によって準備が必要です。

## アプリの更新

0.2.41以降は、アプリの「情報 → アプリの更新」からGitHub Releasesの正式版を確認できます。GitHubへのログインは不要です。

0.2.40以前は従来の配布サイトから移行版0.2.41へ更新できます。その後はGitHub Releasesを使用します。

## このリポジトリについて

このリポジトリはインストーラーと配布説明の公開専用です。アプリケーションの実装ソースは非公開で、ここには含めていません。
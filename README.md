# TOKIBI

会議の時間を、静かに知らせる。

![TOKIBI](brand.png)

Macのカレンダーを読み取り、会議前に風景とともに知らせるアプリです。通知からGoogle Meetなどの会議リンクを開けます。風景と音は、選んだテーマと時間帯に合わせて変わります。

## ダウンロード

**[最新版をダウンロードする](https://github.com/noakouji/tokibi/releases/latest)**

- **[TOKIBI.dmg](https://github.com/noakouji/tokibi/releases/latest/download/TOKIBI.dmg)** — 開いて、TOKIBI.appをApplicationsへドラッグ
- **[TOKIBI.zip](https://github.com/noakouji/tokibi/releases/latest/download/TOKIBI.zip)** — ZIPで受け取りたい方はこちら

このリンクはバージョンが変わっても同じです。no plan inc.名義のDeveloper ID署名・Apple公証済みの配布版を掲載しています。GitHubアカウントは不要です。

**対応：macOS 14 Sonoma以降 / Apple Silicon・Intel Mac**  
macOS 14は最低OSのビルド検査までで、実機起動は未確認です。macOS 15（両CPU）・macOS 26（Apple Silicon）では自動テストを実施しています。

## はじめる

1. ダウンロードしたDMGを開き、TOKIBI.appをApplicationsへドラッグします。ZIPの場合は展開してアプリ本体をアプリケーションフォルダへ移します。
2. Googleカレンダーを使う方は、Macの「カレンダー」アプリにGoogleの予定が表示されるか確認します。まだ表示されない場合は「システム設定 → インターネットアカウント」でGoogleアカウントを追加し、「カレンダー」をオンにします。
3. TOKIBIの初期設定で「Macのカレンダーを使う」を選び、アクセスを許可します。2.21をお使いの場合は「Appleカレンダーを使う」を開き、「Appleのカレンダーに接続」を選びます。Macに同期した予定には、テスター登録なしで通知を設定できます。

「Googleカレンダーに接続」はGoogleアカウントに直接ログインする方法です。現在は登録済みテスターが利用できます。ここでGoogleの画面に「アクセスをブロック」と出たら、そのタブを閉じて手順2・3で接続してください。初期設定はTOKIBIの「設定 → 一般 → 初期設定を開く」から開き直せます。

通知音は最初はオフです。設定からオンにできます。通知を試す機能も設定から有効にできます。

## 更新する

2.20以降では、起動中に新しいバージョンを自動で確認します。通知でインストールを選ぶと、TOKIBIが更新されて再起動します。すぐに確認するには「設定 → 一般 → アップデートを確認…」を押してください。古いバージョンでこの項目が見当たらない場合は、TOKIBIを終了し、最新版のアプリで置き換えてください。

## プライバシーと問い合わせ

予定は自分のMac上で読み取り、通知に使います。広告や利用状況の収集はありません。任意の議事録フォルダ検索もMac内で行い、議事録を外部AIへ自動送信しません。

不具合や使い方の相談は[Issues](https://github.com/noakouji/tokibi/issues)へ。公開の場所なので、予定の件名や参加者名、会議URL、認証情報などは書かないでください。

このリポジトリはアプリの配布用です。インストールには上記のDMGまたはZIPを使ってください。

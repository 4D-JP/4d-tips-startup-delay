# 4d-tips-startup-delay
Sleep briefly before On Startup (experimental workaround for Yosemite/Japanese Input)

About
---
プラグインの```Info.plist```ファイルの```StartupDelayTime```キーを編集してください。デフォルト値は，```1```(秒)です。

```On Startup```データベースイベント（クライアントまたはデスクトップ版）の前（ログインの後）に指定した時間，メインスレッドをスリープさせます。

**注記**: ログイン前にプラグインを実行することはできませんので，[デフォルトユーザー](http://doc.4d.com/4Dv15/4D/15/Setting-a-Default-User.300-2045407.ja.html)を設定し，[CHANGE CURRENT USER](http://doc.4d.com/4Dv15/4D/15/CHANGE-CURRENT-USER.301-2006453.ja.html)などで独自にログインを処理する必要があります。

OS X 10.10 Yosemiteで4Dのスタートアップを遅らせたほうが良いかもしれない理由については[こちら](http://www.4d.com/jp/blog/yosemite-japanese-input.html)をご覧ください。OS X 10.11 El Capitanでは必要ないかもしれません。

サンプル```4DB```のDesignerパスワードは```1```です。

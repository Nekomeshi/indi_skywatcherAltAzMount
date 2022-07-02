# indi_skywatcherAltAzMount

Indi 1.9.6でSE-AT100Nに接続しようとするエラーで接続できないのを救済するためのindi driverです。
サポートするプラットフォームは

OS:Raspberry PI OS buster 32bit
Indi:1.9.6

です。AstRPi5 で動作確認しています。

ファイルをダウンロードしたら、ダウンロードしたフォルダで下記のコマンドを実行し、indi driverを入れ替えてください。

$ chmod a+x indi_skywatcherAltAzMount
$ sudo mv /usr/bin/indi_skywatcherAltAzMount indi_skywatcherAltAzMount.org
$ sudo cp indi_skywatcherAltAzMount /usr/bin

動作確認はAstRPiでSE-AT100Nに接続できるところまでしか実施していません。その先でエラーが発生した場合こちらで確認できるとは限らないので、申し訳ありませんがサポートは保証できません。本家で正しく修正されるまでのつなぎ、としてご使用ください。



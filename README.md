# THE IDOLM@STER SHINY COLORS 事前登録自動ツール

![THE IDOLM@STER SHINY COLORS](https://idolmaster-shinycolors.bxd.co.jp/pc/static/img/top/logo.png)

シャイニーカラーズ(シャニマス)の事前登録自動ツールです。複数のメールアドレスを一気に登録することができます。

このツールはメールアドレスジェネレーターではないので、登録したいメールアドレスを事前に用意してください。

ほかの言語でこのページを読みます：[正體中文](README.zh-tw.md)、[English](README.en.md)。

## 使い方

1. Python 3 をインストールします。
2. [リリースページ](https://github.com/HatsanK/ImasShinyColorsPreregistrationTool/releases/latest)から`Source code`をダウンロードして、解凍します。
3. `src/mail_addresses.txt`に登録したいメールアドレスを入力します。一行につき一つずつ入力してください。例：

```
Hazumi_Nanagusa@283pro.com
Mano_Sakuragi@283pro.com
```

4. `src`フォルダで次のコマンドをターミナルで入力します：

```
python registrator.py
```

5. 自動登録が完了したあと、エンターキーを押してプログラムを終了します。
6. ほかのメールアドレスを探して、ステップ3からもう一度やります。

# THE IDOLM@STER SHINY COLORS 事前登錄輔助程式

![THE IDOLM@STER SHINY COLORS](https://idolmaster-shinycolors.bxd.co.jp/pc/static/img/top/logo.png)

為了減輕各位製作人進行事前登錄的辛勞，本輔助程式誕生了。不管幾十幾百幾千個信箱，按個按鈕一次搞定。（網路通訊需要時間，如登錄數量不少請耐心等候。）

本程式並非信箱產生器，請事先準備欲登錄的信箱。

閱讀其他語言說明：[日本語](README.md)、[English](README.en.md)。

## 如何使用

1. 安裝Python 3.
2. 從[Releases頁面](https://github.com/HatsanK/ImasShinyColorsPreregistrationTool/releases/latest)下載`Source code`並解壓縮。
3. 在`src/mail_addresses.txt`一行一行輸入欲登錄的信箱。例如：

```
Hazumi_Nanagusa@283pro.com
Mano_Sakuragi@283pro.com
```

4. 在`src`資料夾於終端輸入以下指令：

```
python registrator.py
```

5. 待登錄完畢，按Enter鍵關閉程式。
6. 準備其他信箱，回到第3步繼續作業。
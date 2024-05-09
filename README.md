# 星際公民繁體中文(台灣本地化修正)翻譯計畫
此計畫旨在針對遊戲內容、設定選項以及部分機器翻譯內容進行台灣本地化修正，並基於現實專業資料與遊戲世界觀架構的深入研究來提供頂尖水準的翻譯。

--------------------------------------------------

## **重點改進內容**
- 遊戲內翻譯之台灣本地化
- 遊戲設定選項 (使用受遊戲界與UI&UX設計圈推崇的常用語彙)
- 來自社群翻譯中的錯誤翻譯
- 部分機翻內容

--------------------------------------------------

## **文件下載**
﻿
- [**SCTT 下載**](https://sctranslator.danidomen.com/download?locale=cn_traditional&hash=4ff20a445456db1ef318f3b1c000b481)
> 註解：下載完畢後請將文件副檔名改為 ".ini"，否則將會無法使用翻譯文件 。
- [**翻譯修正建議**](https://forms.gle/ThwfANhAvqo2NbfE8)

--------------------------------------------------

## **安裝方式** - 自動安裝 I (建議)
此方法最簡單快速，但需要安裝 [星際公民盒子](https://ref.gamer.com.tw/redir.php?url=https%3A%2F%2Fjihulab.com%2FStarCitizenCN_Community%2FStarCitizenDoctor%2F-%2Freleases) 才能使用。星際公民盒子有自帶繁體中文翻譯，但翻譯內容為簡體中文直譯，未經過台灣本地化修正，並且缺少部分文本翻譯內容，因此不推薦使用。

**影片教學：**
https://www.youtube.com/watch?v=Ei1ZdvlBVPs

此安裝方式由 `星际公民汉化组` 提供 / [網站](https://ref.gamer.com.tw/redir.php?url=https%3A%2F%2Fwww.starcitizenzw.com%2F)

--------------------------------------------------

## **安裝方式** - 自動安裝II
此方法目前只適用在那些將遊戲本體安裝在 系統碟(如D槽) 以外的玩家，如果你的遊戲安裝在系統碟的話，進行自動安裝時將會被系統權限阻擋。

**步驟：**
- 點選 [這裡](https://hsinyu-chen.github.io/SC-localization-installer/public/) 前往安裝畫面。
- 依照畫面上的說明將 **ini文件** 拖曳到方框或是直接點選方框。
- 選擇一種安裝方式。
- 享受你的繁體中文本地化翻譯！

此安裝方式由 `dynameis_tw` 提供 / [Github 原始碼](https://github.com/hsinyu-chen/SC-localization-installer)

--------------------------------------------------

## **安裝方式** - 手動安裝

**步驟：**
- 在以下路徑中創建一個新資料夾：
 - `\StarCitizen\LIVE\data\Localization\New Folder`
- 將資料夾重新命名為：
 - `chinese_(traditional)`
- 將先前翻譯好的 global.ini 檔案放入該資料夾中
- 在 user.cfg 檔案中加入一行 CVAR 指令：
 - `g_language = chinese_(traditional)`
- 更新後，正常啟動遊戲。

如果你沒有 “user.cfg” ，可以按以下步驟創建一個：
1. 創建一個文字文件，並將其命名為 “user.txt“ 
2. 將副檔名由 .txt 更改為 .cfg
3. 將 “user.cfg” 放入路徑：\StarCitizen\LIVE
4. 可使用記事本或其他文字編輯器開啟並編輯 “user.cfg”。


此安裝方式由 `sipher.hsieh` 提供 / [Discord 伺服器](https://discord.com/channels/843863687844200488/1168098715525976094)

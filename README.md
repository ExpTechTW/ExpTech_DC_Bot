# ExpTech_Discord_Bot GitHub
<img alt="Discord" src="https://img.shields.io/discord/857181425908318218">
編程、設計、創意、實用
<br>
努力成為真正的高手
<br />
<p align="center">
  <a href="https://github.com/ExpTech-tw/Example/">
    <img src="image/ExpTech.png" alt="ExpTech" width="150" height="150">
  </a>
  <h3 align="center">ExpTech</h3>
  <p align="center">
    ! 用科技創造無限可能 !
    <br />
    ·
    <a href="https://github.com/ExpTech-tw/Example/issues">錯誤回報</a>
    ·
  </p>
</p>

# 項目概要
* 這是一個由 ExpTech.tw 開發的 Discord 機器人
* [邀請鏈接]( https://reurl.cc/Xloo6D)
* 官方 [Discord](https://discord.gg/rkPu3msUf3)

# 索引
- [開始](#開始)
  - [啟動服務](#啟動服務)
- [權限](#權限)
- [指令](#指令)
  - [指令列表](#指令列表)
- [常見問題](#常見問題)
- [貢獻者](#貢獻者)

# 文檔
## 開始
#### 啟動服務
* 1.邀請 Discord 機器人
* 2.使用 /et bot register 啟動服務並獲取 API Key
* 3.若 API Key 洩漏 請使用 /et bot resetAPIKey
* 4. API 用法請參考 [這裡](https://github.com/ExpTechTW/API/blob/%E4%B8%BB%E8%A6%81%E7%9A%84-(main)/README.md)

## 權限
- 4 - owner - 擁有者
- 3 - admin - 管理員
- 2 - helper - 幫手
- 1 - user - 普通用戶 (默認)
- 0 - guest - 訪客或熊孩子 (禁用所有指令)

## 指令
#### 指令列表
- [/et](#et)
  - [bot]()
    - register
    - resetAPIKey
  - [set](#set)
    - urlChecker
    - certifiedNameChange
- [/mc](#mc)
  - [je](#je)
    - certified
    - user
  - [be](#be)
    - certified
    - user

# /et
## bot
#### register 
- 完整指令: ```/et bot register```
- 加入版本: 21w52-pre1
- 權限: ≥ 4
- 支援: ```Server```
- 默認: ```null```
- 選項: ```null```
- 說明: 每個伺服器可以申請一個 API Key 用來啟動 ExpTech_Discord_Bot 的服務
，或是用來自製機器人，每個 API Key 的每日請求限制為 50000 次。

#### resetAPIKey
- 完整指令: ```/et bot resetAPIKey```
- 加入版本: 21w52-pre
- 權限: ≥ 4
- 支援: ```Server```
- 默認: ```null```
- 選項: ```null```
- 說明: 用來向 ExpTech API 請求重置 API Key

## set
#### urlChecker
- 完整指令: ```/et set urlChecker [選項]```
- 加入版本: 21w52-pre1
- 權限: ≥ 3
- 支援: ```Server```
- 默認: ```false```
- 選項: ```false``` ```true```
- 說明: 用來檢測惡意網址的功能

#### certifiedNameChange
- 完整指令: ```/et set certifiedNameChange [選項]```
- 加入版本: 21w52-pre1
- 權限: ≥ 3
- 支援: ```Server```
- 默認: ```false```
- 選項: ```false``` ```true```
- 說明: 認證後更改用戶暱稱

# /mc
## je
#### certified
- 完整指令: ```/mc je certified [玩家代號]```
- 加入版本: 21w52-pre1
- 權限: ≥ 1
- 支援: ```Server```
- 默認: ```null```
- 選項: ```String```
- 說明: Minecraft Java Edition 帳號認證

#### user
- 完整指令: ```/mc je user [玩家代號/UUID]```
- 加入版本: 21w52-pre3
- 權限: ≥ 1
- 支援: ```Server``` ```User```
- 默認: ```null```
- 選項: ```String``` ```Int```
- 說明: Minecraft Java Edition 玩家數據獲取

## be
#### certified
- 完整指令: ```/mc be certified [玩家代號]```
- 加入版本: 21w52-pre1
- 權限: ≥ 1
- 支援: ```Server```
- 默認: ```null```
- 選項: ```String```
- 說明: Minecraft Bedrock Edition 帳號認證

#### user
- 完整指令: ```/mc be user [玩家代號]```
- 加入版本: 尚未完成
- 權限: ≥ 1
- 支援: ```Server``` ```User```
- 默認: ```null```
- 選項: ```String``` ```Int```
- 說明: Minecraft Bedrock Edition 帳號認證

# 常見問題
#### 問題列表
- [Warn](#Warn)
  - [未知的參數值](#未知的參數值)
  - [查無此用戶數據](#查無此用戶數據)
  - [此伺服器已申請服務](#此伺服器已申請服務)

## Warn
#### 未知的參數值
- 問題原因: 這是由於指令末端附加參數項無法正確讀取其值所導致的
- 解決方法: 輸入指定參數

#### 查無此用戶數據
- 問題原因: 這是由於該用戶尚未被建立資料庫，因此無法記錄其權限或等級所導致的
- 解決方法: 讓該用戶隨意輸入內容並發送至任意頻道，觸發資料庫校驗，即可修正問題

#### 此伺服器已申請服務
- 問題原因: 這是由於該伺服器已申請過 API Key
- 解決方法: 使用該伺服器已有的 API Key 來請求服務，無須再次申請

# 貢獻者
- 程式開發
  - whes1015
- 協助除錯
  - Andrew07145849

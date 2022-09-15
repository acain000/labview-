# 電磁閥

此為一XControl練習

功能為自vi中輸入Boolean訊號到XControl

XControl可判斷輸入訊號並依常開常閉設定給出電磁閥狀態並進行記錄

參考[Xcontrol與Xnode的說明與簡單程式撰寫(LabVIEW筆記)](https://youtu.be/Cye2YCLNnss)

[介面連結](https://github.com/acain000/labview-/new/main/%E9%9B%BB%E7%A3%81%E9%96%A5#%E4%BB%8B%E9%9D%A2)

[說明連結](https://github.com/acain000/labview-/new/main/%E9%9B%BB%E7%A3%81%E9%96%A5#%E8%AA%AA%E6%98%8E)

[設定連結](https://github.com/acain000/labview-/new/main/%E9%9B%BB%E7%A3%81%E9%96%A5#%E8%A8%AD%E5%AE%9A)


## 介面
![介面](https://media.discordapp.net/attachments/727145000575434802/1019890372446523433/unknown.png)


 
## 說明

將右下電源開關打開後開始進行Boolean判斷

透過Booleann按鈕控制輸入訊號

當圖片顯示綠色代表電磁閥閉合

圖片無色時即表示處於開放狀態

每次數值變動皆會記錄

紀錄之資訊包括時間、電源開關狀態、輸入資料狀態、開閉狀態、常開常閉設定狀態

每次開啟關閉皆不會覆蓋過往紀錄

若須刪除舊紀錄則須手動刪除  


## 設定

有三個路徑必須在使用前便設定好(如圖)

![使用前設定](https://cdn.discordapp.com/attachments/727145000575434802/1019891319851724870/unknown.png)

常開常閉設定則可在使用期間任意改變

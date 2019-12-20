# apx515_ Digital Recording (A-D-PC) for Microphone Input   


-  接線方式說明
  1. 將 APx 系列的 Analog Output 連接到受測音效裝置的 Line input。
  2. 開啟專案檔 **PC Line-in Audio Performance Test.approjx**。（File > Open Project…） 
   * 此專案檔並無付，有付的檔名應是**PC Audio Recording Performance Test**
  
- Full Scale Input Voltage (FSIV) 

  1. 用滑鼠點選 APx500 軟體左側 Navigator 區 **Full Scale Input Voltage**。 

     ![](https://i.imgur.com/hHJMC8b.png)

  2. 停止所有的 wave 播放作業。

  3. PC 音量控制： 

     ​	(1) 設定 PC 音量之前一定要確認您在調整的是正在受測的音效裝置。 

     ​	(2) 將 PC 音量控制切換到錄音模式，選取 Line-in，其它音源設定於靜音模式， 確認左右增益平衡調整在中間位置。

     ​	![](https://i.imgur.com/pr7UDZb.png)
  
     ​	(3) Line-in 音量增益調到 0dB 位置，請聯絡你的 Sound Chip 供應商取得設定 音量增益的方法，如果另有主音量或硬體音量可調，請一併調到 0dB 位置。
  
  4. 設定錄音取樣率為 48ks/sec，格式為 16 位元 LPCM wav 檔 。 (若錄的檔案不是wav檔則需要轉檔)
  
  5. 將 APX500 Generator 設定為 ON 後，啟動受測音效裝置錄音 約 5~10 秒，錄音完成後請存檔 於「音樂\LW-100mV.wav」，請勿更改檔名及存放位置。
  
  6. ![](https://i.imgur.com/BhT3tZm.png)
  
     ![](https://i.imgur.com/AF0nNd8.png)
  
  7. 存檔後點擊**Analyze**![](https://i.imgur.com/Wna85dJ.png) 即可於觀測區中顯示錄音後的數位 Level 值，記錄該 數位輸出的 Level 值-XdBFS。
  
     ![](https://i.imgur.com/4Qh9xZx.png)
  
  8. 將 APX500 Signal Generation Level 的單位改成 dBrG，將 Level 值設定為 X dBrG。(記得點擊點擊**Analyze**)
  
     ![](https://i.imgur.com/rPqffLR.png)
  
  9. 再將 Level 的單位改回 Vrms，即可顯示受測音效裝置的 FSIV 值。 
  
  10. 進入 Signal Path Setup，將 Output Reference 的 dBrG 設定為 FSIV 值。
  
      ![](https://i.imgur.com/UAz2ONm.png)
* Sample Frequency Accuracy 
  1. PC 音量控制：維持之前設定的位置不變。 
  
  2. 用滑鼠點選 APx500 軟體左側 Navigator 區 Sample Frequency Accuracy。
  
     ![](https://i.imgur.com/iCKkEvD.png)
  
  3. 將 APX500 Generator 設定為 ON 後，啟動受測音效裝置錄音約 5~10 秒，錄 音完成後請存檔於「音樂\LW-SFA.wav」，請勿更改檔名及存放位置。
  
  4. 存檔後點擊 ![](https://i.imgur.com/Wna85dJ.png)即可於觀測區中顯示 Sample Frequency Accuracy 值。 
* Magnitude Response
  1. PC 音量控制：維持之前設定的位置不變。 
  
  2. 用滑鼠點選 APx500 軟體左側 Navigator 區 Magnitude Response。
  
     ![](https://i.imgur.com/VpitwWg.png)
  
  3. 將 APX500 Generator 設定為 ON 後，啟動受測音效裝置錄音約 5~10 秒，錄 音完成後請存檔於「音樂LW-MR.wav」，請勿更改檔名及存放位置。
  
  4. 存檔後點擊![](https://i.imgur.com/Wna85dJ.png) 即可於觀測區中顯示 Magnitude Response。 
* THD+N vs Frequency 
  1. . PC 音量控制：維持之前設定的位置不變。 
  
  2. 用滑鼠點選 APx500 軟體左側 Navigator 區 THD+N vs Frequency。 
  
     ![](https://i.imgur.com/910Izao.png)
  
  3. 啟動受測音效裝置開始錄音後立即按下![](https://i.imgur.com/tl6J49t.png)令 APx 系列開始產生訊號 供受測音效裝置錄音。
  
  4. 錄音完成後請存檔於「音樂\LW-THD+N.wav」，請勿更改檔名及存放位置。 
  
  5. 存檔後點擊![](https://i.imgur.com/Wna85dJ.png) 即可於觀測區中顯示 THD+N vs Frequency 
* Dynamic Range
  1. PC 音量控制：維持之前設定的位置不變。 
  
  2. 用滑鼠點選 APx500 軟體左側 Navigator 區 Dynamic Range。 
  
     ![](https://i.imgur.com/WoirSTq.png)
  
  3. 將 APX500 Generator 設定為 ON 後，啟動受測音效裝置錄音約 5~10 秒，錄 音完成後請存檔於「音樂\LW-DR.wav」，請勿更改檔名及存放位置。
  
  4. 存檔後點擊 ![](https://i.imgur.com/Wna85dJ.png)即可於觀測區中顯示 Dynamic Range 值。 


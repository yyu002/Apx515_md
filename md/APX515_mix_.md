# APX515_mix_

## Apx515_index

- apx515_Index : 所有文件目錄說明
- apx515_instrument :儀器與資源網站
- apx515_1_Pre_install : 測試環境軟硬體安裝設定
- apx515_2_Full_Scale_Output_Voltage
- 2~8為DIGITAL PLAYBACK (ANALOG LINE OUTPUT JACK)音源輸出
- apx515_3_ Sample_Frequency_Accuracy & Magnitude_Response
- apx515_4_THD+N_vs_Frequency & Dynamic Range With Signal Present
- apx515_5_ Noise_Level_During_System_Activity
- apx515_6_Crosstalk vs Frequency (Right to Left) & Crosstalk vs Frequency (Right to Left)
- apx515_7_ Interchannel Phase Delay
- apx515_8_wave mixer
- apx515_9_ Digital Recording (A-D-PC) for Microphone Input

## Apx515-儀器與資源網站
### 儀器介紹:

-   APx515 B Series Audio
    Analyzer:https://www.ap.com/analyzers-accessories/apx515/
-   主機圖片:
    ![](http://cn.ap.com/upfile/image/20181219/20181219115019_68436.jpg)
-   配件:
    - 電源線
    
      <img src="https://images.plurk.com/4YjAn2ovfFDS0NvdxRHvly.jpg" style="zoom: 33%;" />
    
    - PC interface線(轉USB)
    
      <img src="https://images.plurk.com/2LD1A6OxTsMH3SIMUjl5CC.jpg" style="zoom:33%;" />
    
    - 音訊線
    
      <img src="https://images.plurk.com/49tSV0kkHQR0iCMoKTqh3o.jpg" style="zoom:33%;" />
    
    - 負載電阻(4)
    
      <img src="https://images.plurk.com/49tSV0kkHQR0iCMoKTqh3o.jpg" style="zoom:33%;" />
    
      <img src="https://images.plurk.com/7itC6jiLiZdOHsxcLjx6rN.jpg" style="zoom:33%;" />
    
    - 光碟
    
      <img src="https://images.plurk.com/YhVBB4hwrCHf5qfRSwt2S.jpg" style="zoom:33%;" />
    
    - 隨身碟
    
      <img src="https://images.plurk.com/4NXdCIO7SMxAw22h5Bsaf6.jpg" style="zoom:33%;" />
    
    - 麥克風
    
      ​																												
      
    - 光纖音訊線
      
      <img src="https://images.plurk.com/3unMAu7EGePCrRAhxiMEfu.jpg" style="zoom:33%;" />
      
      <img src="https://images.plurk.com/1lKcxwTExPQLv4Ar9Gbokc.jpg" style="zoom:33%;" />

### 網站資源 :

-   APx500 Measurement Software:
    https://www.ap.com/download/apx500-measurement-software-22/
-   新2700系列 [http://www.audiotech.com.tw/DnLoad/2700 Series
    Brochure.pdf](http://www.audiotech.com.tw/DnLoad/2700%20Series%20Brochure.pdf)
-   APx系列音頻分析儀
    http://www.audiotech.com.tw/DnLoad/APx\_Series\_Catalog.pdf
-   標準麥克風 http://www.audiotech.com.tw/DnLoad/378M32.pdf
-   耳機量測治具
    http://www.audiotech.com.tw/DnLoad/AECM206\_HTF\_Data\_Sheet.pdf
-   喇叭、麥克風量測周邊 http://www.audiotech.com.tw/DnLoad/APx1701.pdf
-   APx500軟體選購指南
    http://www.audiotech.com.tw/DnLoad/APx500\_Software\_Options.pdf

-   精音儀科技有限公司　http://www.audiotech.com.tw
    電話：(02)2792-0199　傳真：(02)2794-9462 產品諮詢：嚴鴻麟
    <neilyen@ms1.hinet.net>, 0912-343212

## Apx515\_1\_Pre\_install : 測試環境軟硬體安裝設定

1.  軟體安裝:

-   使用公用電腦打開APx500 5.0
    ![](https://i.imgur.com/jVvsmBa.png)即可使用

-   若要安裝APx500到自己電腦中請使用

    -   附贈之光碟:光碟裝有軟體與測試音訊檔

    -   雲端檔案 :
    	- 官網下載 : Apx500 (連結為5.0)
          https://www.ap.com/download/apx500-measurement-software-24/
          註冊登入後即可下載，解壓縮後運行APx500Setup安裝
    	
        - WAVE檔 :
		  進入共享檔連結(Dropbox):https://www.dropbox.com/s/6j1ci4fw0qzwg3n/PC%20Audio%20Test%20For%20APx500.rar?dl=0

		- 並下載
		
		   ![](https://i.imgur.com/B5tBMxG.png)
		
		- PDF為Apx的代理公司所寫教學，把檔案解壓縮即可找到.wave與寫好的project
		 ![](https://i.imgur.com/ZkDZV1Q.png)

2.  硬體:

適用Apx500為所有APx系列:

-   APx515
-   APx525
-   APx526
-   APx555
-   APx585
-   APx586
-   **此為Apx515，在開啟APx500 5.0時選擇515**


3.  連結PC設定:

-   接線方式說明 :

	1.  利用立體耳機插頭至RCA 立體母座的轉接頭將受測音效裝置的Line output 連
    接至Analog Inputs 的BNC 輸入端。
	2.  在與Analog Inputs 的BNC 輸入端並聯的香蕉端子間連接10kΩ/0.5W 之負載
    電阻。(白/紅色電阻)
	3.  在開啟APx500 5.0前必須先把pc
    interface與待測物接好，若先開啟程式軟體可能會無法連上

-   確認連上 : 

	![](https://i.imgur.com/5Zh73Wo.png)
    再接好PC與待測物後打開APx500會聽見細微的開關聲，代表PC有連上。
    再進入畫面左下角可以看見有訊號。 
    播放待測物音訊給515一個不同的訊號觀察訊號是否會變動，如有變動則為連上。

    * 撥放音效前 :
      ![](https://i.imgur.com/a6EiMvG.png)
    * 播放音效後 : 
      ![](https://i.imgur.com/FeBOIBJ.png) 
      *此音效為播放範例Full Scale Output Voltage-48K-16b*


4.  專案檔 :

-   直接使用廠商給的專案即可:

-   PC Audio Playback Performance Test.approjx

-   File \> Open Project

    ![](https://i.imgur.com/YKzvZEL.png)

其餘設定 :

1.  Sequence 選擇@48Ks/sec：取樣率48ks/sec。(位於左上)

    ![](https://i.imgur.com/oUEcGZW.png)

2.  Signal Path 選擇Line Output @48K：取樣率48ks/sec。(左欄)

    ![](https://i.imgur.com/9i3yCZD.png)

    選擇48k即可不用選96k，若是不想讓程式跑太多可以先關掉產生report的部分

    本章中所有使用到的wave 檔位於\PC Audio Test For APx500\Waveform

## Apx515\_2\_Full\_Scale\_Output\_Voltage : FSOV值測量


-   注意先開啟專案 PC Audio Playback Performance Test.approjx

1.  點選左側Navigator區Full Scale Output Voltage

![](https://i.imgur.com/n3jU5wM.png)

2.  音量控制(在此受測物為同個pc的音源故作此範例win10系統) :

-   只選擇wave與主音量聲音(只保留.wave檔的聲音)，其他音量靜音，確認左右增益在中間位置。

    -   ![](https://i.imgur.com/NUjdspD.png "fig:")
-   Wave 音量增益調到 0dB 位 置，請聯絡你的 Sound Chip 供應商取得設定
    Wave 音量增益的方法。

    -   參閱 :
        https://support.microsoft.com/zh-hk/help/4027981/windows-10-how-to-set-up-and-test-microphones

    -   調整音量增益 請選取 [開始] \> [設定] \>[音效] \> [聲音控制台]
        調整耳機與麥克風音量增益

    ![](https://i.imgur.com/vN0OQJs.png)

    -   雙擊後可至等級設定 
        
        ![](https://i.imgur.com/keYBKV4.png)
        ![](https://i.imgur.com/9dD1eoV.png)

3.  開啟 Wave 檔 Full Scale Output
    Voltage-48K-16b.wav，並設定成反覆播放模 式。

4.  播放 Wave 檔，觀測輸出的失真值(THD+N Ratio)，調整 Main volume 使輸出
    達到失真低於 1%（建議低於 0.2%）的最大輸出。

![](https://i.imgur.com/gDF3w7I.png)

5.  設定 **References dBrA, dBrB**

 (1) 用滑鼠點擊切換至References設 定畫面 (Reference \> Set dBr)

 ![](https://i.imgur.com/byY2IEr.png)

 (2) 用滑鼠點擊 **[Set dBr...]**，於跳出的 **Set dBrA, dBrB
**對話框中分別用 滑鼠點擊**[Set A]**和**[Set B]**，即可 記錄 Full Scale
Output Voltage (以下簡稱 FSOV) 值，同時也完成了 dBrA 和 dBrB 參 數
的設定，0 dBrA 和 0 dBrB 分別為 Ch A 和 Ch B 的 Full Scale Output
Voltage，設定後點 擊 **[Close]**。

![](https://i.imgur.com/wcjGTwe.png)


## Apx515\_3\_ Sample\_Frequency\_Accuracy & Magnitude\_Response

-   注意先開啟專案 PC Audio Playback Performance Test.approjx

-   Sample Frequency Accuracy

    1.  用滑鼠點選 APx500 軟 體左側 Navigator 區 Sample Frequency
        Accuracy。 ![](https://i.imgur.com/drxI444.png)

    2.  PC 音量控制：維持FSOV測試時 的位置不變。
    3.  開啟 Wave 檔 **Full Scale Output Voltage-48K-16b.wav**，並設定成
        反覆播放模式。
    4.  播放 Wave 檔，在 APx500 軟體右側的觀測區可以看到 Sample
        Frequency Accuracy ， 該值的允許 誤差為± 0.02%，因此 量測值應介
        於 **99.98% ～ 100.02% **之間。
        ![](https://i.imgur.com/gGjlVse.png)

-   Magnitude Response 及 Interchannel phase difference

1.  用滑鼠點選 APx500 軟體左側 Navigator 區 Magnitude Response。

    ![](https://i.imgur.com/jLfrFeE.png)

2.  PC 音量控制：維持FSOV測試 時的位置不變。

3.  開啟 Wave 檔 **Line-out Magnitude Response-M48k.wav，取消反覆播放模式**。
    
4. signal definition 調整成**Line-out Magnitude Response-M48k.wav**

   ![](https://i.imgur.com/A3qWb9g.png)

5. 用滑鼠點選**start**![](https://i.imgur.com/C3aR7Sq.png) 後，播放 Wave 檔即可量測得 Magnitude Response。

6. 用滑鼠點選 APx500 軟體左側 Navigator 區 Magnitude Response 之下的
   Phase 項 目，可觀測 Interchannel phase difference。

   -   Magnitude Response

   ![](https://i.imgur.com/HYyCHnr.png)

   -   Interchannel phase difference

   ![](https://i.imgur.com/RqHOmgp.png)



* gif :https://camo.githubusercontent.com/740ff4d996d119bdbba8cce2a8ccc71b71e4e76a/68747470733a2f2f692e696d6775722e636f6d2f415655444241572e676966

  ![](https://i.imgur.com/AVUDBAW.gif)

## Apx515\_4\_THD+N\_vs\_Frequency & Dynamic Range With Signal Present

- 注意先開啟專案 PC Audio Playback Performance Test.approjx

- THD+N vs Frequency

  1. 用滑鼠點選 APx500 軟體左側 Navigator 區 THD+N vs Frequency。

     ![](https://i.imgur.com/lSQYNzM.png)

  2. PC 音量控制：維持FSOV測試時 的位置不變。

  3. 開啟 Wave 檔 THD+N vs Frequency-48K-16b.wav，取消 反覆播放模式。

  4. 用滑鼠點選 **start**![](https://i.imgur.com/C3aR7Sq.png)後，播放 Wave 檔即可量測得 THD+N vs Frequency。

     ![](https://i.imgur.com/cJ1EYPG.png)

- Dynamic Range With Signal Present

  1. 用滑鼠點選 APx500 軟體左側 Navigator 區 Dynamic Range With Signal
     Present。

     ![](https://i.imgur.com/mrezv8N.png)

  2. PC 音量控制：維持FSOV測試時 的位置不變。

  3. 開啟 Wave 檔 Dynamic Range-48K-16b.wav，並設定成反覆播放模式。

  4. 播放 Wave 檔，即可於觀測區中顯示 Dynamic Range 值。

     ![](https://i.imgur.com/9OKKIAg.png)

## Apx515_5_Noise Level During System Activity

- 注意先開啟專案 PC Audio Playback Performance Test.approjx

- Noise Level During System Activity 

  1. 用滑鼠點選 APx500 軟 體左側 Navigator 區 Noise Level During System Activity 

     ![](https://i.imgur.com/o4TQtaG.png)

  2. PC 音量控制：維持FSOV測試時 的位置不變。

  3. 開啟 Wave 檔 **Zero-Triangular Dithered.wav**，並設定成反覆播放模式。

  4. 播放 Wave 檔，即可於觀測區中顯示 Noise 值。

     ![](https://i.imgur.com/ESfztu2.png)



##  Apx515_6_Crosstalk vs Frequency (Left to Right) & Crosstalk vs Frequency (Right to Left)

- 注意先開啟專案 PC Audio Playback Performance Test.approjx

- Crosstalk vs Frequency (Left to Right) 

  1. 用滑鼠點選 APx500 軟體左側 Navigator 區  Crosstalk vs Frequency (Left to Right) 

     ![](https://i.imgur.com/CUEQods.png)

  2. PC 音量控制：維持FSOV測試 時的位置不變。

  3. 開啟 Wave 檔 **Line-out Magnitude Response-M48k.wav，取消反覆播放模式**。

  4. 用滑鼠點選![](https://i.imgur.com/C3aR7Sq.png) **start**後，播放 Wave 檔即可量測得 Crosstalk vs Frequency (Left to Right) 

     ![](https://i.imgur.com/nAIAEYP.png)

-  Crosstalk vs Frequency (Right to Left)   

  1.  用滑鼠點選 APx500 軟體左側 Navigator 區 Crosstalk vs Frequency (Right to Left)。
  ![](https://i.imgur.com/evP2SIJ.png)

  2.  PC 音量控制：維持FSOV測試時 的位置不變。 

  3. 開啟 Wave 檔 **Line-out Crosstalk vs Frequency-R48k.wav**，取消反覆播放模式。 

  4. 用滑鼠點選**start** ![](https://i.imgur.com/C3aR7Sq.png)後，播放 Wave 檔即可量測得 Crosstalk vs Frequency (Right to Left)。 

     ![](https://i.imgur.com/TSztoED.png)

## Apx515_7_Interchannel Phase Delay

- 注意先開啟專案 PC Audio Playback Performance Test.approjx

- 請利用第三節量到的 **Interchannel Phase Difference**數據計算 Interchannel Phase Delay。 

- Interchannel Phase Delay 

  1.  顯示 Interchannel Phase Difference 數據 

     ![](https://i.imgur.com/RqHOmgp.png)
     ![](https://i.imgur.com/tnZSCOa.png)


  2. 將 **Interchannel Phase Difference** 數據存成 Excel 檔「Line-out Interchannel Phase Difference.xlsx」。 

     ![](https://i.imgur.com/WLK59w6.png)

  3. 開啟範例 **Line-out Interchannel Phase Delay.xlsx**，套用 sec 欄位公式將 deg 欄位的角度值換算成延遲時間。 


## Apx515_8_手動調整 wave mixer 的位置： 


- 注意先開啟專案 PC Audio Playback Performance Test.approjx
  1. 用滑鼠點選 APx500 軟體左側 Navigator 區 Full Scale Output Voltage。 
  
     ![](https://i.imgur.com/zlccUbk.png)
  
  2. 開啟 Wave 檔 Full Scale Output Voltage-48K-16b.wav，並設定成反覆播放模式。 
  
  3. 先將 Wave mixer、Main volume 及硬體音量調整鈕（如果有的話）至**最大增益** 的位置。 
  
  4. 播放 Wave 檔，觀察此時的失真值(THD+N)是否低於 1%？如果是的話則結束，手動調整繼續測試。如果不是的話則繼續以下的調整。 
  
  5. 先降低 Wave mixer 的增益，看是否能顯著的降低輸出的失真值？如果是的話 則將 Wave mixer 固定於最明顯降低輸出的失真值的位置，如果不是的話則保 持 Wave mixer 於原來的位置。
  
  6. 接下來依序調整 Main volume 及硬體音量調整鈕（如果有的話）的增益，看是 否能顯著的降低輸出的失真值？如果是的話則將該 mixer 固定於最明顯降低輸 出的失真值的位置，如果不是的話則保持該 mixer 於原來的位置 
  
  7. 調整 mixer 使輸出達到最大而且波峰沒有被截去的現象（THD+N 應低於 1%， 建議低於 0.2%）。 


## Apx515_9_Digital Recording (A-D-PC) for Microphone Input   

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




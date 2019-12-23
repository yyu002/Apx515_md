apx515\_2\_Full\_Scale\_Output\_Voltage : FSOV值測量
====================================================

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

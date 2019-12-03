apx515\_1\_Pre\_install : 測試環境軟硬體安裝設定
================================================

1.  軟體安裝:

-   使用公用電腦打開APx500 5.0
    ![](https://i.imgur.com/jVvsmBa.png)即可使用

-   若要安裝APx500到自己電腦中請使用

    -   附贈之光碟:光碟裝有軟體與測試音訊檔

    -   雲端檔案 :
    -   官網下載 : Apx500 (連結為5.0)
        https://www.ap.com/download/apx500-measurement-software-24/
        註冊登入後即可下載，解壓縮後運行APx500Setup安裝
    -   WAVE檔 :
        進入共享檔連結:https://moss.tao.inventec.com/sites/TaoPA/Shared%20Documents/Forms/AllItems.aspx?RootFolder=%2fsites%2fTaoPA%2fShared%20Documents%2fCommon%20Shared%20Documents%2fHP%20Commonality%20Spec&FolderCTID=&View=%7bCDE88EF1-B653-45A5-A2AD-91100151C416%7d

並下載![](https://i.imgur.com/Nx6OHDy.png)

      PDF為Apx的代理公司所寫教學，把檔案解壓縮即可找到.wave與寫好的project

      ![](https://i.imgur.com/ZkDZV1Q.png)

2.  硬體:

適用Apx500為所有APx系列:

-   APx515

-   APx525

-   APx526

-   APx555

-   APx585

-   APx586

    此為Apx515，在開啟APx500 5.0時選擇515

3.  連結PC設定:

-   接線方式說明 :(照片、類比數位、光纖、左右聲道、麥克風耳機待補)

1.  利用立體耳機插頭至RCA 立體母座的轉接頭將受測音效裝置的Line output 連
    接至Analog Inputs 的BNC 輸入端。
2.  在與Analog Inputs 的BNC 輸入端並聯的香蕉端子間連接10kΩ/0.5W 之負載
    電阻。
3.  在開啟APx500 5.0前必須先把pc
    interface與待測物接好，若先開啟程式軟體可能會無法連上

-   確認連上 : ![](https://i.imgur.com/5Zh73Wo.png)
    再接好PC與待測物後打開APx500會聽見細微的開關聲，代表PC有連上。

​ 再進入畫面左下角可以看見有訊號。 ​
播放待測物音訊給515一個不同的訊號觀察訊號是否會變動，如有變動則為連上。

    * 撥放音效前 :
      ![](https://i.imgur.com/a6EiMvG.png)

-   播放音效後 : ![](https://i.imgur.com/FeBOIBJ.png) *此音效為播放範例
    Full Scale Output Voltage-48K-16b*

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



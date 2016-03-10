<img src="/pc_logo/probecube logo.png" width="250"> 

##專案簡介
ProbeCube是個基於開放硬體的物聯網專案，鼓勵大眾動手製作WiFi連網的機器來偵測空氣品質並組織共同的觀測地圖。

附註: 觀測地圖的部分目前已改以g0v的專案方向開發，請參考連結。


##運作原理
感測器-Arduino(wifi)-Thingspeak-觀測地圖

##支援的硬體
*Arduino NANO, UNO + Adafruit CC3000 wifi module

*Particle Photon

##感測項目
* 溫度/濕度 - DHT22
* 空氣中總揮發物質(VoCs) - FIGARO tgs2602
* 懸浮微粒PM2.5 - PMS3003(G3) 或 GP2Y1010AU0F

##如何開始
1. 準備材料
2. 焊接或使用麵包板連接各部元件組成ProbeCube
3. 註冊[Thingspeak](https://thingspeak.com/)帳號並設定上傳channel
4. 將程式碼客製修改後編譯寫入ProbeCube
5. ProbeCube的資料將會上傳至Thingspeak
6. 到ProbeCube共同觀測地圖提交你的Thindspeak Channel ID分享資料(已併入g0v專案，請參考連結)

##連結

* 詳細組裝及設定步驟圖文 (撰寫中)
* [g0v零時空汙觀測網](http://g0vairmap.3203.info/)及其[原始碼](https://github.com/immortalmice/Real-time-Air-Quality-Map)

##範例
* 麵包版接線示意

<img src="https://github.com/Lafudoci/ProbeCube/blob/master/Particle Photon based/ProbeCube_v099_20160225_bb.png" width="500">


* [Thingspeak channel 範例](https://thingspeak.com/channels/26769) - 即時上傳的空氣觀測資料!

<img src="/pc_pics/ts_demo.JPG" width="500">


* 由arduino uno為主板搭配組裝後的ProbeCube  

<img src="https://github.com/Lafudoci/ProbeCube/blob/master/Arduino with cc3000wifi based/pc_uno_shield_demo.jpg" width="500">


* 由Particle Photon為主板組裝後的ProbeCube裝上3D print外殼搭配Blynk app的呈現

<img src="https://github.com/Lafudoci/ProbeCube/blob/master/Particle Photon based/pc_photon_blynk_demo.jpg" width="500">

* 由Particle Photon為主板組裝後的ProbeCube裝上3D print外殼現

<img src="https://github.com/Lafudoci/ProbeCube/blob/master/pc_pics/2016-03-09 15.53.55.jpg" width="500">

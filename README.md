## 網路設備

![網路設備](https://user-images.githubusercontent.com/91168069/138025692-d365b6a0-9c17-4f4f-a843-13af720cd9f7.png)

## 路由器(Router)- [資料來源](https://zh.wikipedia.org/wiki/%E8%B7%AF%E7%94%B1%E5%99%A8)

###
- 是一種電訊網路裝置，提供路由與轉送兩種重要機制，可以決定封包從來源端到目的端所經過的路徑（host到host之間的傳輸路徑），這個過程稱為路由；將路由器輸入端的封包移送至適當的路由器輸出端（在路由器內部進行）。路由工作在[OSI模型的第三層]()。
- 是連接兩個以上[個別網路]()的裝置。

## 中繼器（Repeater）- [資料來源](https://zh.wikipedia.org/wiki/%E4%B8%AD%E7%BB%A7%E5%99%A8)

###
- 一個將輸入訊號增強放大的類比裝置。是用來加強纜線上的訊號,延展網路長。

## 集線器(Hub)- [資料來源](https://zh.wikipedia.org/wiki/%E9%9B%86%E7%B7%9A%E5%99%A8)

###
- 是指將多條乙太網路雙絞線或光纖集合連接在同一段物理媒介下的裝置。集線器是運作在[OSI模型中的實體層]()，可以讓其連結的裝置工作在同一網段。
- 集線器會把收到的任何數位訊號，經過再生或放大，這會造成訊號之間碰撞的機會很大，而且訊號也可能被竊聽。
- [半雙工]()

## 橋接器(Bridge)- [資料來源](https://zh.wikipedia.org/wiki/%E6%A9%8B%E6%8E%A5%E5%99%A8)

###
- 橋接器將網路的多個網段在資料鏈路層連接起來。
- 橋接器是將兩個[獨立]()的網路連接起來，就如同單一網路。

## 交換器(Switch)- [資料來源](https://zh.wikipedia.org/wiki/%E7%B6%B2%E8%B7%AF%E4%BA%A4%E6%8F%9B%E5%99%A8)

###
- 是一種多埠的網橋，在資料鏈路層使用[MAC位址]()轉發資料。通過引入路由功能，一些交換器也可以在網路層轉發資料。
- [全雙工]()

## L2 switch- [資料來源](https://home.gamer.com.tw/creationDetail.php?sn=4247878)

###
- 將實體在網路之間建立邏輯連結，在傳輸過程中處理流量控制及錯誤偵測。
- 將實體層的數位訊號封裝成訊框(data frame)，其中訊框包含資料鏈結層的MAC位址，用以識別主機資料來源位址。主要用於[區域網路]()上。

## L3 switch(ASIC)
- [資料來源 1](https://zh.wikipedia.org/wiki/%E7%89%B9%E6%AE%8A%E6%87%89%E7%94%A8%E7%A9%8D%E9%AB%94%E9%9B%BB%E8%B7%AF)  
- [資料來源 2](https://home.gamer.com.tw/creationDetail.php?sn=4247878)

### 
- L3 的交換器又稱為IP Switch或Switch Router，透過專屬的[ASIC 晶片]()來解析第三層表頭以達到傳送目的，因此通常可以提高到每秒百萬封包的效能以及數十個高速乙太網路連接埠之容量。 L3 Switch 的路由表可以對VLAN 做更有效的管制，讓廣播封包不會無限制的傳送。
- 運用在[網路層]()
- [特定應用積體電路（Application Specific Integrated Circuit: ASIC)]()，是由特定使用者要求和特定電子系統的需要而設計、製造。 體積小、重量輕、功耗低、可靠性高、性能高、保密性強。

## L4 switch- [資料來源](https://home.gamer.com.tw/creationDetail.php?sn=4247878)

###
- 用於[傳輸層]()中，可辨識傳輸層內TCP或UDP埠號(port)，判斷封包是使用哪一種應用協定，在傳遞的封包中加入控制信息，以增加服務品質，達成重新導向(redirect)或伺服器的負載平衡(Load Balancing)

## L7 switch- [資料來源](https://home.gamer.com.tw/creationDetail.php?sn=4247878)

###
- 用於[應用層]()中，提供網路應用服務，包含DHCP或瀏覽器等，可做Cookie Switch、Session Switch、Url Switch 或是 CDN。

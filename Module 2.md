# Module 2 連接與溝通 線上: The Internet, Websites, Media
## The Internet
Network，高等研究計劃署網路(ARPANET)，1969年開始使用，一開始連結了四台分布在不同地方的電腦，作為network的主機，到1984年，已經發展到1000台的主機，現今更是有公家或私人數以百萬的主機被不同的機構所擁有。

> host 主機
> 是指服務其他台電腦連接上網路，以及裝置之間相互連結，具有唯一IP地址並能夠發送和接收數據的任何電腦或設備，通常可以在網路上快速地進行數據/訊息傳遞。Server是host的其中一種類型。

The Internet是networking的基礎技術去發展不一樣的服務，也推動了networking的技術，從美國國防高等研究計劃署(ARPA)開始，一開始的計畫目的有兩個，(1.) 允許不同地方的科學家可以分享他們的研究資訊以及跨地合作 (2.) 即使部分網路因核攻擊等而癱瘓或損壞，也能正常運作。
> 技術的開發跟時代背景也有相關

至今，Internet提供了許多資源與服務給電腦和行動裝置，例如web能夠取得資訊、手機或電腦可以進行訊息/影音通訊等，都是透過了Internet，連結了網路上數以百萬的企業、政府機構、教育機構或個人。透過不同的網路協定，也提供了其他網路服務，例如email寄信、線上聊天室(例如：line, messenger)、線上討論區(例如：巴哈姆特)等。

### 連接到Internet的方式
分為有線跟無線這兩個種類，顧名思義就是裝置之間連線到網路的方式是透過實體絞線還是無線的方式，例如數據機有分為有線跟無線兩種，無線的數據機、無線訊號接收器，在內建的過程中會嵌入必要的技術(例如:WiFi、衛星等)來連接上無線網路。

> 數據機(modem, modulator demodulator)：用於在網路上的傳輸轉換數據或其他項目，讓數據可以進行裝置之間傳輸的硬體。
> 無線訊號接收器(dongle)：連接在電腦上的小型設備，附上額外的功能，包括提供無線連接、增加儲存空間、支持安全身份驗證等。

目前大部分會使用寬頻(broadband)，因為他傳遞數據的速度比較快速，而且不會中斷，透過寬頻可以使用網路上的各項服務，比如說玩線上遊戲、下載資料等。

### 常見的網路頻寬服務技術
* 有線
    1. 同軸電纜網路服務(Cable Internet Service)：透過**有線電視同軸電纜**，與纜線數據機連線。
    2. 數位用戶線路(Digital Subscriber Line, DSL)：透過**電話網**，與DSL數據機提供連線。
    3. 光纖電纜FTTH(Fiber to the premises)：透過**光纖**，與數據機提供連線。
* 無線
    1. WiFi：透過**無線電**，與內嵌可WiFi接收的裝置連線。許多公開場合，例如學校、機場等，會利用WiFi提供熱點(提供裝置無線網路)上網，有些不限制使用，有些會需要密碼。
    2. 行動寬頻：透過**手機無線電網路**，與內嵌的相應科技(例如3G、4G、5G)裝置或者是無線數據機等連線。有些人會使用行動網路頻寬，開啟熱點來網路分享(tethering)給其他裝置。
    3. Fixed wireless 固定無線：透過**無線電**，利用屋頂上安裝**dish-shaped**(如下圖)，進行之間的連線。
![tower1-243x300](https://hackmd.io/_uploads/H1QYZlBdC.png)
(圖源網路)
    4. Satellite Internet service 衛星網路服務：透過**衛星**，利用**衛星天線**連線到衛星數據機。

> 少數比較偏鄉的居家用戶，因為頻寬沒辦法涵蓋到居住的範圍會使用撥號連線(dial-up)，以電話線類比訊號來傳輸資料，用戶的電腦使用數據機打ISP提供的電話號碼，建立連接後，數據通過電話線傳輸。 

### 網際網路服務供應商 ISP
是一種提供免費/付費網路的行業，會有許多網速、頻寬(bandwidth)、服務不一樣的方案給使用者選購，例如使用非對稱數位用戶迴路(Asymmetric Digital Subscriber Line, ADSL)傳統電話線路調解技術，來符合一般網際網路使用者習慣和特性，提供高速上網服務。隨著行動裝置的普及，現在也有mobile service provider，也被稱為wireless data provider，是由ISP所提供給行動裝置的服務。
:::success
寬頻(broadband)跟頻寬(bandwidth)
* Broadband（寬頻）指的是一種高速網路連接的技術，能夠同時傳輸多種類型的數據（如影片、音頻和文本）。
* Bandwidth（頻寬）指的是網絡能夠在特定時間內傳輸的數據量，通常以每秒位數（bps, bits per second）為單位來衡量。資料的大小以小到大排序有KB、MB、GB、TB、PB、EB、ZB、YB，以2^10倍增長。
:::

## Websites
### 網頁
當Internet在1960年代被發明以後，The World Wide Web(www, W3C)在1990年代誕生，是Internet的應用之一，能用簡易方式取得線上資訊的瀏覽工具，也促使更多人使用Internet。
每個網上的電子文件被稱為 **網頁(webpage)** ，分為靜態跟動態兩種，網頁內包含了文字、圖表、動畫、影音等多樣的資訊，每個網頁都有自己的**網址(web addresses; Uniform Resource Locator, URL)** 。
* **靜態網頁**時的資訊內容皆會相同，不會隨著時間等變動，例如單一的新聞頁面；
* **動態網頁**則是會進行動態的調整，比方說氣象資訊網頁、售票網頁等等。

這些網頁與相關的圖文、影音項目等資訊會收集在**網站(website)**，並且儲存在**網站伺服器(web server)** 中。
> 網站伺服器是傳遞網頁要求到你的裝置的computer，一台網站伺服器可以儲存多個網站，除了儲存網頁外，也負責處理用戶請求，運行後端應用，並與資料庫連接。

### 瀏覽器
使用者可以利用電腦或其他可以連網路的裝置，連接網路後，從**瀏覽器(browser)** ，例如Chrome、Edge...等，可以在起始頁面(home page)查找想要的相關資訊，取得網站內的資訊並且觀看，瀏覽器也可以新增分頁(tabbed browsing)，可以同時在瀏覽器中開啟多個分頁，進行不同網頁的切換，使用者也可以將這些分頁以群組(tab group)的方式管理或儲存。
除了透過瀏覽器要求資訊之外，網站可透過**訊息來源(web feed)** 將最新資訊傳播給使用者，使用者透過訂閱來取得資訊，通常大量的媒體、部落格、線上新聞等都會提供使用者這項服務，節省使用者檢查網站內容的時間。

行動裝置有專用的瀏覽器，稱為行動裝置瀏覽器(mobile browser)，例如Safari，與電腦的瀏覽器頁面大小不相同，網頁工程師可以利用HTML、CSS、JS等程式語言設計網頁，並透過響應式網頁設計(Responsive Web Design, RWD)調整網頁在不同裝置上的呈現方式，避免畫面超出範圍，方便各種裝置閱讀。

### web/mobile APP 網頁/手機應用程式
* Web App (Web應用程式) 簡單來說是由前端 (Front-end) 及後端 (Back-end) 所組成。直接透過網站就可以使用，通常會儲存使用者的資料在主機中，使用者可以透過自己的裝置 **雲端儲存(cloud storage)** 他們的檔案，大多數的Web APP是可以免費取得的，那企業可能會透過廣告或者是限制功能來營利。手機也有網頁應用程式，叫做mobile web app。
:::info
雲端運算技術也有很多內容可以補充，比方說常聽到的IaaS、PaaS、SaaS，之後有空會再補充。概念如下圖：
![60620c160aca0839d1e5038c_SaasPaaSIaaS](https://hackmd.io/_uploads/HJr6Bv8d0.png)
圖源：[https://www.virtasant.com/blog/iaas-vs-paas-vs-saas-a-complete-overview](https://)
:::
* Mobile APP (手機應用程式)就是常見的APP，設計給智慧型手機、平板電腦等行動裝置運行的應用程式，可以透過手機裡的APP store或者直接從網路上進行下載。通常這類型的APP取得資料的方式需要透過手機內建置的不同功能硬體，例如鏡頭、麥克風、GPS等。
> 全球定位系統GPS(Global Positioning System)：利用衛星進行地球地面的定位與導航。GPS接收器透過分析衛星軌道上24顆衛星的至少3個單獨的衛星訊號來定位，可以是手持式、可安裝式、嵌入式，例如天線、無線電接收器等，多數智慧型手機使用的是嵌入式GPS。
>GPS如何運作可以看這裡： [https://www.youtube.com/watch?v=U3eX6QKS9kY](https://)

有些企業會同時提供Web APP 跟Mobile APP，透過雲端的方式儲存資料，讓你可以在電腦上網頁瀏覽、下載Web APP到本機中察看或者下載Mobile APP讓你可以隨身攜帶。
:::info
舉個例子🌰：
Google雲端硬碟，你可以從瀏覽器進到自己的雲端硬碟帳戶使用，也可以下載他的應用程式在本機端，這樣可以方便斷線時作業，等到恢復連線後再上傳這些內容，也可以在手機下載APP，搭車的時候就可以看了。
:::

:::success
前端後端 v.s. 前台後台
* 前端後端
    * 前端：通常包括網頁或應用程序的視覺和交互設計。前端開發主要涉及到網頁的設計和呈現，確保用戶可以看到和使用網頁或應用程式。
    * 後端：支持前端的服務器端部分，處理業務邏輯、資料庫操作、身份驗證等。後端開發主要涉及到伺服器、應用和資料庫的邏輯和功能。
* 前台後台
以日常生活的內容聯想，
    * 前台：直接與客戶或用戶互動的部分，例如客服、銷售等被稱為前台。那網頁上的前台就是提供給使用者互動的部分，例如各種類別的按鈕、問卷表單等等。
    * 後台：支援企業運營但不直接與客戶互動的部分，如會計、人力資源等。網頁上的後台就是工程師內部協助設定網頁上內容的部分，例如網站上銷售甚麼產品、產品資訊等。

其他可參考資訊：[https://www.youtube.com/watch?v=7cl45LAJ9aQ](https://)
:::

### 網站的種類
網站有許多不一樣的種類，比如說(1.) 搜尋引擎、(2.) 社群媒體、(3.) 學術資訊網站、(4.) 媒體分享網站、(5.) 訂購網站、(6.) 新聞網站、(7.) 教育網站、(8.) 企業網站、(9.) 部落格、(10.) 維基和協作網站、(11.) 健康照護網站、(12.) 科學網站、(13.) 娛樂網站、(14.) 銀行與金融網站、(15.) 旅遊網站、(16.) 地圖網站、(17.) 零售網站、(18.) 求職求才網站、(19.) 電商網站、(20.) 入口網站、(21.) 內容整合網站(content aggregator)等。
> 網站種類有許多，以上種類皆為課本列點說明項目，這邊不多做額外說明。

## Media
網站中的數位媒體有三大種：圖片、聲音、影片，常見的格式如下：
1. 圖片：BMP(Bitmap)點陣圖、GIF(Graphics Interchange Format)、JPEG(Joint Photographic Experts Group)、PNG(Portable Network Graphics)、TIFF(Tagged Image File Format)、SVG（Scalable Vector Graphics）基於XML的向量圖，縮放不會失真、WEBP（Web Picture format）
2. 聲音：MP3(最大宗，在各系統上被廣泛支持)、WAV（Waveform Audio File Format）未經過壓縮、WMA（Windows Media Audio）由微軟開發，音頻經過壓縮
3. 影片：MP4、MOV（QuickTime File Format）、WMV（Windows Media Video）由微軟開發、MOV(QuickTime File Format)由蘋果公司開發、WEBM（Web Media）專為網頁設計的格式，

另外還有外掛(plug-ins)，你可以下載瀏覽器的一些外掛程式，來使用不一樣的功能。Chrome的擴充功能：[https://chromewebstore.google.com/category/extensions?hl=zh-TW](https://)
> 我自己很喜歡的擴充：[https://chromewebstore.google.com/detail/meowsing/bbfbeaopdnagijhehlhajpjnfghdhohm](https://) 貓咪伴讀超可愛的

## 資料怎麼被傳遞
不管是透過哪種的連線方式，資料的傳遞你可以想像成一車車的包裹(封包)，透過很多條公路相連，有省道也有高速公路進行運輸，也會有他們的主要幹道(Internet backbone)，而主要幹道的流量(traffic)會比較高一些，這些Data會經過一個又一個的network，直到他送到目的地。
為了要送到正確的位置，我們的設備會有一個獨一無二的 **IP address(Internet Protocol address)** 提供網路上的地址，地址的寫法有分為兩種，IPv4、IPv6。

>* 網址：包含了這個網頁使用的網路協定、主機名稱、網域名稱、路徑、網頁名稱，課本舉例： http://www.nps.gov/history/preserve-places.htm ，在這個網址當中，使用http網路協定、主機名稱www、網域名稱 nps.gov、路徑history、網頁名稱preserve-places.htm，使用者可以輸入網址後，在獲得IP位置以後，從瀏覽器向網頁伺服器發出要求，再從伺服器回傳網頁資訊到使用者的設備。
>* IPv6 是一種較新的IP address格式，用來解決IPv4空間不足的問題。
:::success
**常見的網路協定**：
* HTTP (HyperText Transfer Protocol)	網際網路上的主要通信協定，用於傳輸網頁。
* HTTPS (HyperText Transfer Protocol Secure)	HTTP的加密版本，使用SSL/TLS協定來加密通訊以保護數據傳輸的安全性。

更多常見的網路協定可參照第一章
:::
因為這些網址不好記憶，所以提供了 **Domain Name(網域名稱)** 方便記憶，舉例而言，google.com的".com"叫做頂層網域top-level domain(TLD) 是網域名稱最後一個點之後的所有內容，就是一種domain name。透過 **domain name system(DNS)** 的方式，進行對於domain name的儲存，以及轉換為 IP 位址，使瀏覽器能夠存取網站和其他網路資源，而DNS server 通常也是由ISP進行連接提供的網路服務。
> TLD由Public Technical Identifiers(PTI)批准和控制頂級域名。

## 安全瀏覽網站的方式
1. 驗證網站是否安全，比如說確保網站使用HTTPS協定。
2. 關閉定位，在瀏覽器的設定裡，禁用對位置的訪問權限。
3. 清除瀏覽歷史紀錄，在瀏覽器的設定裡，管理自己在各網站上的cookies，並且定期清除瀏覽器的歷史紀錄、緩存和cookie。
![圖片1](https://hackmd.io/_uploads/S1xwewIOA.jpg)
(圖源網路)
4. 不儲存密碼，避免在瀏覽器中儲存密碼，避免駭客取得。
5. 使用網路釣魚過濾器，防止誤觸惡意網站。
6. 封鎖彈跳式廣告彈出，可以透過安裝廣告攔截的瀏覽器外掛，如AdBlock Plus，避免惡意網站彈出。
7. 使用無痕模式，理論上這樣瀏覽器不會保存您的瀏覽紀錄，但是今年初的時候報出使用無痕仍然被企業追蹤使用資訊：[https://www.cna.com.tw/news/afe/202404020077.aspx](https://)😢😢
8. 使用代理伺服器，隱藏使用者的IP位置，也可以使用VPN（虛擬私人網絡），來保護自己的隱私安全。

除此之外，因為任何人都可以在網路發布內容，網路上的資訊並不一定是正確的，大家需要具備媒體識讀的能力。課本列出了下列七點建議評估網站，
1. 附屬機構：網站應由一個值得信賴的機構支持，確保信息沒有偏見。
2. 受眾：網站應針對合適的讀者群撰寫內容。
3. 權威性：網站應列出作者及其相關資格。
4. 內容：網站內容應良好規劃，例如裡面的分頁連結要可以跳轉。
5. 時效性：網頁上的資訊應該是最新的。
6. 設計：網站頁面應該要可以被快速下載，UI設計應該要一目了然，容易操作。
7. 客觀性：網站應包含少量廣告且無偏見。

最後小提醒，在網路上請勿因為匿名對於他人進行 **網路霸凌(cyberbullying)**，大家一起維持**網路禮節(netiquette)**。~~不知道為甚麼想到電腦網路的三項交握。~~
![cooperation](https://hackmd.io/_uploads/HkBmQwUOC.png)


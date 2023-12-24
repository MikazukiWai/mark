# **軟體工程超市銷售管理系統**


# 主題


隨著科技的迅速發展，資訊的爆炸性增長成為不可忽視的現象。為了順應資訊社會急速演進的潮流，企業必須利用互聯網搭建新的營運模式。在這個背景下，連鎖超市已成為眾多企業欲採納的新模式之一。


本設計主要實現集人性化、高效率、便利性等優點於一身的超市管理系統，完成使用者管理、分類資訊、商品資訊管理、銷售記錄管理、採購記錄管理、會員等級設定、會員資訊管理等功能模組。

系統透過瀏覽器與伺服器通信，實現資料的互動與變更。

只需透過一台電腦，輕鬆操作系統，實現數據通訊管理。

整個系統的設計過程充分考慮了資料的安全、穩定性及可靠性等問題，並確保操作過程簡單。

本系統透過科學的管理方式和便捷的服務提升了工作效率，同時降低了資料儲存上的錯誤和遺漏的風險。


# 1

**1.1**

隨著社會經濟的不斷發展，人們生活水準的日益提高，人們對於食品和日用品等商品的要求也越來越高。

超市作為一種方便、快速、物美價廉的購物場所已逐漸被廣大消費者所接受。

然而，由於傳統的管理模式存在著許多弊端，使得許多企業在進行現代化管理時遇到了很大困難。

在超市中採用先進的管理資訊系統來對其進行科學管理是非常重要的一個面向。

因此，為了使企業能夠更好地適應市場環境，提高管理水平，必須加強對超市管理系統的研究與應用。

本文以某大型連鎖超市為對象，透過分析該超市現有的管理系統，發現其中存在一些問題並提出解決方案。

本論文針對眾多超市產業普遍存在的「重經營輕管理」現象，結合現代超市的特點，設計出一套適合大型超市的管理系統，可以有效解決這些問題。本系統具有操作簡單、介面友善、實用性強、安全性高等優點。

它不僅能滿足超市管理人員日常業務處理需要，而且還能幫助他們及時掌握超市運行狀態信息，以便及時發現問題、及時處理。

本系統對超市管理者來說有著十分重大的意義。成功實施本系統不僅能為企業節省大量人力物力成本，更重要的是可以大幅提升公司的工作效率，以達到提高經濟效益、增加效益的目的。

**1.2**

本系統主要完成了以下幾個方面工作：根據客戶需求，對系統功能進行規劃，並確定了系統功能模組及其劃分方案。

根據系統業務邏輯，對系統總體架構進行規劃，將整個系統分為前台和後台兩部分，其中前端主要是銷售模組、訂單處理模組和系統管理模組。

根據系統功能分析，對系統各功能模組進行詳細的使用案例分析。

針對系統效能最佳化問題，從系統資源調度角度出發，給予對應的解決方案。

為了驗證本文設計方法的有效性，本文也進行了原型系統的實作。經過測試表明，本文提出的系統設計方案能夠較好地滿足企業對於超市經營管理的需要，並且能很好地解決企業面臨的一系列問題，因此可以推廣應用於其他類似的資訊系統開發當中。

然而，由於系統的複雜性和多樣性，系統仍有許多不足，有待進一步改進和改進。

希望透過未來的努力，讓系統更加智慧化，更好地為顧客服務。

隨著電子商務的快速發展，超市的資訊化程度也得到很大程度的提升。

而傳統的管理模式已經無法適應新時期的發展要求，如何有效的解決這些問題就成為當前迫切需要研究的課題。

本計畫旨在結合超市經營管理的特點，運用現代資訊科技對現有超市管理系統進行整合和升級改造，從而達到降低營運成本，提高管理效率的目的。


# 2 基於Python的超市管理系統分析 


系統分析是發展一個專案的先決條件，透過系統分析可以很好的了解系統的主體使用者的基本需求情況，同時這也是專案的開發的原因。進而對系統開發進行可行性分析，通常包括技術可行性、經濟可行性等，可行性分析同時也是從專案整體角度進行的分析。接著就是對專案的具體需求進行分析，分析的手段一般都是透過使用者的用例圖來實現。下面是詳細的介紹。

**2.1 可行性分析**

（1）經濟可行性： 在專案上使用的工具大部分都是當下流行開源免費的，所以在開發前期，開發時用於專案的經費將會大大降低，不會讓開發該軟體在專案啟動期受到經費的影響，所以經濟上還是可行的。盡量用最少的花費去滿足使用者的需求。省下經費用於人工費，以及設備費用。將在無紙化，高效率的道路上越走越遠。 所以經濟可行性沒問題。 

（2）操作可行性： 此次專案設計參考了幾個該模式下網站的開發案例，對他們的操作介面分析，將眾多案例結合在一起，突出以人為本簡化操作，所以具有基本計算機知識的人都會操作本項目。 因此操作可行性也沒有問題。 

（3）技術可行性： 技術可行性指的是對於搭建框架的可行性，以及有更優秀的技術出現時系統的技術更新換代的納新性如何，開發時間成本費用比如何。 現有的python技術能夠迎合所有電子商務系統的建置。開發這個基於Python的超市管理系統的時候我採用了python+MYSQL用以運行整體程式。 

綜上所述技術可行性也沒有問題。 

（4）法律可行性： 從開發者角度來看，python和MYSQL是網路上開源且免費的，在智慧財產權方面不會產生任何法律糾紛。 從使用者使用角度來看，只要不再系統上販賣違禁品，對系統做出條約協議，杜絕非法支付即可。 綜上所述法律可行性也沒有問題。

**2.2系統流程分析**

業務流程是用一些特定的符合和線條來進行演示使用者在使用系統時的過程，在進行系統分析的時候，業務流程可以幫助開發人員更好的理解業務，發現錯誤，完善系統。 


### 2.2.1 資料增加流程 


用戶成功登錄系統後就能夠實現增加數據的操作，增加數據的編號是特定的，系統生成，用戶不能隨意填寫，除了編號以外，其他增加信息用戶自己填寫，填寫後的信息經過系統驗證，驗證合法透過就顯示增加數據成功了，相反的話，就沒有增加成功，

![image](https://github.com/MikazukiWai/mark/blob/main/image/2-1.png)

**圖2-1顯示的就是在增加數據時的流程。**


### 2.2.2 資料修改流程


資料修改時的流程和上面介紹的資料増加時的流程差不多,如圖 2-2

![image](https://github.com/MikazukiWai/mark/blob/main/image/2-2.png)

**圖2-2資料修改流程圖。**


### 2.2.3 資料刪除流呈


如果系統裡面存在ー些沒有用的資料的話,相關的管理人員可以對這些資料進行刪除,圖2-3

就是資料刪除時的流程圖。

![image](https://github.com/MikazukiWai/mark/blob/main/image/2-3.png)

**圖2-3資料刪除流程圖。**

**2.3系統功能分析**

2.3.1 功能性分析

依照基於Python的超市管理系統的角色,我劃分為銷售人員管理模組,採購人員管理模組和管理員管理樹組造三大部分 。

**採購人員管理模組:**

(1) 採購人員註冊登入: 採購人員註冊為採購人員並登入基於 Python 的超市管理系統: 使用者對個人資料的增刪改查，例如個人資料，密碼修改。

(2) 商品資訊管理: 採購人員進行商品資訊的閲覽，查看管理者發佈的商品資訊。

(3) 銷售記錄: 採購人員進行銷售記錄查詢，查看管理者發布的銷售記錄資訊。


**管理員管理模組：**

（1）登入：管理員的帳號是在資料表中直接設定產生的，不需要進行註冊；

（2）系統使用者管理：點選「使用者管理」此選單時，會出現管理員+採購人員+銷售人員三個子選單，可以對這三個模組進行增刪改查操作；

（3）更多區塊管理：點擊「更多模組」這個選單時，會出現分類資訊+商品資訊管理+銷售記錄管理+採購記錄管理+會員等級設定+會員資訊管理這六個子選單，可以對這六個模組進行增刪改查操作；

（4）商品資訊管理：管理員可以對超市管理系統中現有的商品資訊進行增刪改查。

（5）銷售記錄管理：管理員可以對超市管理系統中現有的銷售記錄資訊進行增刪改查。

（6）會員資訊管理：管理員可以對超市管理系統中現有的會員資訊進行增刪改查。

（7）會員等級管理：管理員對使用者提交的會員等級進行管控。




**2.3.2 非功能性分析**

基於Python的超市管理系統的非功能性需求例如基於Python的超市管理系統的安全性怎麼樣，可靠性怎麼樣，性能怎麼樣，可拓展性怎麼樣等。具體可以表示在如下3-1表格中： 

表2-3-1基於Python的超市管理系統非功能需求表

| 安全性|主要指基於Python的超市管理系統資料庫的安裝,資料庫的使用和密碼的設定必須合乎規範。|
|-------|:-----:|
| 可靠性|可靠性是指基於Python的超市管理系統能夠安裝便用者的指示進行操作,經過測試,可靠性在90%以上。|   
| 效能|性能是基於Python的超市管理系統在市場上成功的必要條件，因此最好要有優越的性能。|  
| 可擴展性|例如資料庫預留多個当性,例如介面的使用等確保了系統的非巧能性需求。| 
| 易用性|使用者只要跟著Python為基礎的超市管理系統的頁面展示内容進行操作,就可以了。| 
| 可維護性|基於Python的超市管理系統開發的可維護性是非常重要的,經過測試,可維護性沒有問題。| 


**2.4 系統用例分析**

透過2.3功能的分析，得出了本基於Python的超市管理系統的用例圖： 

銷售人員使用者角色用例如圖2-3-2所示。

![image](https://github.com/MikazukiWai/mark/blob/main/image/2-3-2.png)

圖2-4 基於Python的超市管理系統銷售人員角色用例圖 

透過2.3功能的分析，得出了本基於Python的超市管理系統的用例圖：

採購人員角色用例如圖2-3-3所示。

![image](https://github.com/MikazukiWai/mark/blob/main/image/2-3-3.png)

圖2-5 基於Python的超市管理系統採購人員角色用例圖

web後台管理上的管理員是維護整個基於Python的超市管理系統中所有資料資訊的。管理員角色用例如圖2-3-4所示。

![image](https://github.com/MikazukiWai/mark/blob/main/image/2-3-4.png)


圖2-6 基於Python的超市管理系統管理員角色用例圖

**2.5本章小結**

本章透過以Python為基礎的超市管理系統的可行性分析、流程分析、功能需求分析、系統用例分析，確定整個系統的實現功能，為程式碼實作和測試提供了標準。

**3 基於Python的超市管理系統整體設計**

本章主要討論的內容包括基於Python的超市管理系統的功能模組設計、資料庫系統設計。

3.1 系統架構設計 

本以Python為基礎的超市管理系統從架構上分為三層：表現層（UI）、業務邏輯層（BLL）、資料層（DL）。

圖片加入

圖3-1基於Python的超市管理系統系統架構設計圖

**表現層（UI）:** 又稱UI層，主要完成本基於Python的超市管理系統的UI互動功能，一個良好的UI可以打打提高用戶的用戶體驗，增強用戶使用本基於Python的超市管理系統時的舒適度。

UI的介面設計也要適應不同版本的基於Python的超市管理系統以及不同尺寸的分辨率，以做到良好的兼容性。UI互動功能要求合理，使用者進行互動操作時必須要得到與之相符的互動結果，這就要求表現層要與業務邏輯層進行良好的對接。 

**業務邏輯層（BLL）:**主要完成本基於Python的超市管理系統的資料處理功能。使用者從表現層傳輸過來的資料經過業務邏輯層處理交付給資料層，系統從資料層讀取的資料經過業務邏輯層處理後交付給表現層。 

**資料層（DL):**由於本基於Python的超市管理系統的資料是放在服務端的mysql資料庫中，因此本屬於服務層的部分可以直接整合在業務邏輯層中，所以資料層中只有資料庫，其主要完成本基於Python的超市管理系統的資料儲存和管理功能。

**3.2 系統功能模組設計**

3.2.1整體功能模組設計 在上一章中主要對系統的功能性需求和非功能性需求進行分析，並且根據需求分析了本基於Python的超市管理系統中的用例。

那麼接下來就要開始對本基於Python的超市管理系統的架構、主要功能和資料庫開始進行設計。基於Python的超市管理系統根據前面章節的需求分析得出，其整體設計模組圖如圖3-2所示。













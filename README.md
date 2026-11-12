# 臺大網路註冊教學

男女舍通用。在開始之前，請先想好要用無線還是有線的方式連接網路。

## 快速導覽

| 章節 | 內容 |
|---|---|
| 01 | [無線網路註冊](#wireless) |
| 02 | [有線網路註冊](#wired) |
| 03 | [常見問題 FAQ](#faq) |
| 04 | [網管聯絡資訊](#network-admin) |

<h2 id="wireless">01 無線網路註冊</h2>

請準備一台無線分享器以及乙太網線，並在宿舍房間進行。

1. **連接網路線**：將乙太網線的一端插進宿舍的網路孔，另一端插進無線分享器的 WAN 網孔（通常在無線分享器的屁屁，請插進顏色跟其他孔不一樣並且寫 WAN 的）。
2. **開啟路由器**：將無線分享器的電源插上並開機，等待其開機。
3. **連接 Wi-Fi**：將電腦連接到該無線分享器分享的 Wi-Fi。

   > 提醒：這時候你可能會看到電腦顯示「無網際網路」，也就是說你還不能正常使用網路，這是正常的。請繼續進行下一步。

4. **進入註冊頁面**：請打開瀏覽器輸入 `https://dorm.ntu.edu.tw/register/index.php` 。你會看到計中的登入頁面，登入。

   登入後你會看到以下畫面：

   <p align="center">
     <img
       src="assets/register1.png"
       alt="計中網路註冊頁面"
       style="width: 100%; max-width: 600px; height: auto;"
     >
   </p>

5. **完成註冊**：點選「註冊電腦於：男/女x舍」。
6. **等待網路啟用**：接下來就會看到這個畫面，代表成功。

   > 成功：註冊完成後等待 5～10 分鐘就可以上網。

   <p align="center">
     <img
       src="assets/register2.png"
       alt="網路註冊成功畫面"
       style="width: 100%; max-width: 600px; height: auto;"
     >
   </p>

<h2 id="wired">02 有線網路註冊</h2>

### 事前準備

乙太網線：

<p align="center">
  <img
    src="assets/rj45.jpg"
    alt="乙太網線接頭"
    style="width: 100%; max-width: 300px; height: auto;"
  >
</p>

如果你的電腦沒有這種孔的話：

<p align="center">
  <img
    src="assets/rj45Laptop.jpg"
    alt="電腦上的乙太網路孔"
    style="width: 100%; max-width: 300px; height: auto;"
  >
</p>

請購買轉接頭，大概會長這樣：

<p align="center">
  <img
    src="assets/adapter.png"
    alt="乙太網路轉接頭"
    style="width: 100%; max-width: 300px; height: auto;"
  >
</p>

### 開始註冊

請在宿舍房間進行。

1. **連接網路線**：將乙太網線的一端插進宿舍的網路孔，另一端插進你的電腦或是透過轉接頭插入到你的電腦。

   > 提醒：這時候你可能會看到電腦顯示「無網際網路」，也就是說你還不能正常使用網路，這是正常的。請繼續進行下一步。

2. **進入註冊頁面**：請打開瀏覽器輸入 `https://dorm.ntu.edu.tw/register/index.php` 。你會看到計中的登入頁面，登入。。你會看到計中的登入頁面，登入。

   登入後你會看到以下畫面：

   <p align="center">
     <img
       src="assets/register1.png"
       alt="計中網路註冊頁面"
       style="width: 100%; max-width: 600px; height: auto;"
     >
   </p>

3. **完成註冊**：點選「註冊電腦於：男/女x舍」。
4. **等待網路啟用**：接下來就會看到這個畫面，代表成功。

   > 成功：註冊完成後等待 5～10 分鐘就可以上網。

   <p align="center">
     <img
       src="assets/register2.png"
       alt="網路註冊成功畫面"
       style="width: 100%; max-width: 600px; height: auto;"
     >
   </p>

<h2 id="faq">03 常見問題 FAQ</h2>

### 硬體與連接

#### Q1. 乙太網線拔不出來怎麼辦？

請輕壓乙太網線凸起的地方，拉出來即可。

#### Q2. 換了電腦、網路卡或轉接頭，需要重新註冊嗎？

- 換轉接頭：需要
- 換電腦：可能需要（如果是用轉接頭連接的話不用）
- 換 Wi-Fi Router：可能需要重新註冊。
- 更換網路線：不需要重新註冊。

---

### 註冊問題

#### Q3. 如果在註冊頁面註冊的時候顯示「MAC 位置重複」怎麼辦？

如果是用無線分享器，可以登入無線分享器的管理頁面，更改 MAC address。

> 注意：MAC 位置重複時，可能需要更改 MAC address；不同轉接頭不一定都能修改。

如果是使用轉接頭連接到電腦，可以嘗試修改 MAC address，不過也有可能沒辦法更改成功。請向輔導員借用無線分享器或是買新的轉接頭。（通常比較便宜的轉接頭會無法修改 MAC address 並且容易撞到 MAC address。）

如果是直接將乙太網線連到電腦，同樣可以嘗試修改 MAC address（如果您的電腦是 Windows 11 的話，請在電腦搜尋「裝置管理員」，點開「網路介面卡」 > Realtek ... > 進階 > 網路卡位置 > 值）。

#### Q4. 換宿舍後，無法重新註冊網路

請聯繫[網管](#network-admin)協助您刪除在舊宿舍的資料，刪除後即可重新註冊。

---

### 網路異常

#### Q5. 有線網路斷斷續續的怎麼辦？

有線網路對碰觸比較敏感，如果是這種情況的話，請嘗試重新插拔乙太網線。

如果碰觸的問題很煩的話可以考慮換成無線的分享器。如果沒有碰到，還是很常斷斷續續的話，請與[網管](#network-admin)聯繫。

#### Q6. 有時候網路很慢怎麼辦？

有可能是用太多網路被限流了，可以到 [`http://140.112.2.249/ntu-quota.php`](http://140.112.2.249/ntu-quota.php) 查詢自己的 IP 的流量。（自己的 IP 可以在電腦的網路介面或是註冊網路的頁面找到或是查詢 IP 的網頁。）相關規定可以參考[宿舍網路規定](https://ccnet.ntu.edu.tw/ccnet/dorm.php)。

#### Q7. 為什麼網路突然被限制，甚至完全不能使用？

除了流量超額，也可能是電腦被列入違規主機名單。如果不確定是不是的話，請聯繫[網管](#network-admin)。

---

### 路由器設定

#### Q8. 無線網路相關設定資訊（一般來說不需要特別處理）

針對宿舍網路，請使用路由模式（Routing Mode）。IP 取得請使用 DHCP Auto。

> 補充：一般來說不需要特別處理這些設定。

#### Q9. 有線網路相關設定資訊（一般來說不需要特別處理）

IP 取得請使用 DHCP Auto。

#### Q10. MAC address 是什麼？

他是網路硬體的身分證，一般來說，如果照著上面的教學步驟做的話，系統會自動偵測你的 MAC address，因此不需要特別設定。

#### Q11. 忘記路由器管理頁面的帳號密碼怎麼辦？

找找看路由器底部標籤。如果忘記自己設定的管理密碼，可能需要恢復原廠設定（Factory Reset），但這會清除原本的路由器設定。

<h2 id="network-admin">04 網管聯絡資訊</h2>

### 需要網管協助？

如果以上方法都無法解決問題，請聯繫宿舍網管或輔導員。

[查看網管聯絡資訊](https://osa_dorm.ntu.edu.tw/AboutUs/NetworkManagementAssistants)

## 參考資料

- [宿舍網路註冊說明](https://ccnet.ntu.edu.tw/ccnet/pages/student_dorm_content/doc/register.pdf)
- [參考教學](https://hackmd.io/@JBWY7SINQ5C32zAOI1PzIg/S1eqgV7oR)

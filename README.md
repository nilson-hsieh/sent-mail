使用限制<br>
一天最多寄送20封<br>
無法選擇固定的寄件人<br>
勿發推銷廣告<br>
使用方法<br>
將資料使用 POST方式傳送至  https://airhot.tw/mail/<br>
接收資料格式<br>
user_id : 授權使用者ID<br>
u_hash : 授權使用者權杖<br>
mail_add : MAIL收件地址<br>
mail_name : MAIL收件者名稱 <br>
mail_title : MAIL標題<br>
mail_project : MAIL內文(以HTML撰寫)<br>
re_page : 傳送完導向的頁面<br>
完成後完成狀態以 GET方式回傳至re_page 頁面<br>
回傳資料格式<br>
statue : 見下表<br>
time : 寄送時間<br>
回傳狀態表<br>
200 資料傳送成功<br>
500 資料格式錯誤<br>
535 使用者認證失敗<br>
550 寄送失敗(請聯絡管理員)<br>
552 超過寄送限制<br>
************************************************************************************
Copyright © 艾爾佳智慧生活 2020<br>
service@airhot.tw

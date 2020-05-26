使用限制
一天最多寄送20封
無法選擇固定的寄件人
勿發推銷廣告
使用方法
將資料使用 POST方式傳送至  https://airhot.tw/mail/
接收資料格式
user_id : 授權使用者ID
u_hash : 授權使用者權杖
mail_add : MAIL收件地址
mail_name : MAIL收件者名稱 
mail_title : MAIL標題
mail_project : MAIL內文(以HTML撰寫)
re_page : 傳送完導向的頁面
完成後完成狀態以 GET方式回傳至re_page 頁面
回傳資料格式
statue : 見下表
time : 寄送時間
回傳狀態表
200 資料傳送成功
500 資料格式錯誤
535 使用者認證失敗
550 寄送失敗(請聯絡管理員)
552 超過寄送限制
************************************************************************************
Copyright © 艾爾佳智慧生活 2020
service@airhot.tw

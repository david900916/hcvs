# hcvs
班級經營管理APP

程式功能：
a.使用者查詢U_AP（積分歷程紀錄，卡片兌換記錄）--勝揚
b.使用者資料管理M_AP（新增，修改，刪除，查詢，以CSV檔案批次新增）--黃瀚
3.卡片兌換AP
4.積分管理AP：1.積分管理(（新增，修改，刪除，查詢，以CSV檔案批次新增） 2.積分查詢 3.排序(Top 10) 
5.最新消息AP
6.可接任務AP
7.卡片使用AP

網頁程式開發資料表：
1.user_data個人資料表：序號SN，使用者號碼8碼(學號，身分證號)UserID，密碼Passwd，班級Class，姓名Name，座號SeatNum，
  身份status(學生s,老師t,管理員m)，積分Point，職業Job，性別Sex，電話Phone，備用欄位Note
2.quest任務積分表：任務ID，任務名稱，職業需求，完成後獲得積分，數量，截止日期，
3.card卡片資料表表：卡片ＩＤ（Ａ999第一碼為分類號，後三碼序號），兌換券名稱，兌換所需積分，
  兌換券剩餘數量（99代表無限），限制身份（Ｘ代表無限制）
4.point exchange 卡片兌換記錄表：兌換日期，兌換人ＩＤ，執行人ＩＤ，兌換券ＩＤ，兌換積分
5.point積分記錄表：日期Date，執行人MID，被登記人UID，事項名稱Item，積分Point，分類Class
6.加減分項目表：序號SN，事項名稱Item，加減積分Point

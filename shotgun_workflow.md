## Shotgun 工作流程

### 產生新專案
![01](https://user-images.githubusercontent.com/42924265/75033664-5b591f00-54e6-11ea-8835-26b54f871f9d.gif)
* 在Projects頁面滑鼠點左上角的  [ + Project ] 按鈕
* 輸入專案名稱，選擇專案的架構格式(可以由其他已經存在的專案作為架構範本)，然後按下 [ Create Project ]

---

### 建立Sequence
![02](https://user-images.githubusercontent.com/42924265/75033674-614f0000-54e6-11ea-960e-5f2029760faf.gif)
* 到目前專案的Sequence頁面，剛建立好的頁面會有 **[ Create a New Sequence]** 按鈕，點選後輸入Seqence名稱再按下 [ Create Sequence] 按鈕即可。
* 另外也可以由左上角的 **[ +Sequence ]**  按鈕建立，點選後輸入Seqence名稱再按下 [ Create Sequence] 按鈕即可。
* 或由 **[ More  / Import Sequences ]** 從Excel表格建立。Excel表格內需有命名為"Sequence Name"的欄位，在其下輸入Sequence序列名稱，然後選擇要傳送到Shotgun的欄位按下 Ctrl + C 複製(注意不要選擇到其他不相關的欄位，像是 id 等，才不會出錯)，再到剛剛import的頁面按 Ctrl + V 貼上 > [ Continue ] > 勾選 "Sequence Name" Use as id  > [ Continue ] > [ Finish and Import ]

---

### 建立Shot
![03](https://user-images.githubusercontent.com/42924265/75033677-6449f080-54e6-11ea-8e7f-b8e2b34ce2bf.gif)
![03-2](https://user-images.githubusercontent.com/42924265/75033685-68760e00-54e6-11ea-9457-763877917d84.gif)
* 到目前專案的Shots頁面，剛建立好的頁面會有 **[ Create a New Shot]** 按鈕，點選後輸入Shot Code和 Sequence名稱再按下 [ Create Shot] 按鈕即可。
* 另外也可以由左上角的 **[ +Shot ]** 按鈕建立，點選後輸入Shot Code和 Sequence名稱再按下 [ Create Shot] 按鈕即可。
* 或由 **[ More  / Import Shots ]** 從Excel表格建立。Excel表格內需有命名為"Shot Code"的欄位，在其下輸入Shot Code序列名稱，建議添加名為"Sequence"的欄位，在其下輸入各卡對應的Sequence名稱。然後選擇要傳送到Shotgun的欄位按下 Ctrl + C 複製(注意不要選擇到其他不相關的欄位，像是 id 等，才不會出錯)，再到剛剛import的頁面按 Ctrl + V 貼上 > [ Continue ] > 勾選 "Shot Code" Use as id  > [ Continue ] > Add thumbnails 加入縮圖(縮圖檔案名稱必須與卡號相同才能配對!!!)  >  [ Finish and Import ]
* 之後若有其他欄位資訊需要上傳也可以使用 **[ More  / Import Shots ]** 從Excel表格複製需要的欄位資訊貼上即可(務必一定要複製"Shot Code"的欄位 + 其他需要的欄位 )，若是已經有建立好的資訊，再一次的上傳就會更新成最新的資料。

---

### 建立Assets
![04](https://user-images.githubusercontent.com/42924265/75033693-6dd35880-54e6-11ea-9926-06edbc6359fe.gif)
* 到目前專案的Assets頁面，剛建立好的頁面會有 **[ Create a New Asset]** 按鈕，點選後輸入Asset Name 和 Type 名稱再按下 [ Create Asset] 按鈕即可。
* 另外也可以由左上角的 **[ +Asset ]** 按鈕建立，點選後輸入Asset Name 和 Type 名稱再按下 [ Create Asset] 按鈕即可。
* 或由 **[ More  / Import Assets ]** 從Excel表格建立。Excel表格內需有命名為"Asset Name"的欄位，在其下輸入各個Asset Name名稱，建議添加名為"Type"的欄位，在其下輸入各Asset對應的Type種類名稱。然後選擇要傳送到Shotgun的欄位按下 Ctrl + C 複製(注意不要選擇到其他不相關的欄位，像是 id 等，才不會出錯)，再到剛剛import的頁面按 Ctrl + V 貼上 > [ Continue ] > 勾選 "Asset Name" Use as id  > [ Continue ] > Add thumbnails 加入縮圖(縮圖檔案名稱必須與Asset名稱相同才能配對!!!)  >  [ Finish and Import ]
* 之後若有其他欄位資訊需要上傳也可以使用  **[ More  / Import Assets ]** 從Excel表格複製需要的欄位資訊貼上即可(務必一定要複製"Asset Name"的欄位 + 其他需要的欄位 )，若是已經有建立好的資訊，再一次的上傳就會更新成最新的資料。

---

### 連結各個Shot內的Assets
![05](https://user-images.githubusercontent.com/42924265/75036822-ad517300-54ed-11ea-8a40-fb0d8aa9ad2f.gif)
* 到目前專案的Shots頁面，於要編輯的卡號的 **Assets** 欄位點選編輯，輸入關聯的Asset名稱即可。可以一次選擇多筆欄位編輯填入相同內容。
* 也可以從由 **[ More  / Import Shots ]** 從Excel表格建立。Excel表格內需有命名為"Shot Code"的欄位，在其下輸入Shot Code序列名稱，再加入命名為"Assets"的欄位，在其下輸入各卡對應的Asset名稱（限定已經在專案Assets頁面建立好的Asset，才能找到"相同名稱"的asset）,多於一個的asset名稱之間以「逗號」分隔即可，然後選擇要傳送到Shotgun的欄位按下 Ctrl + C 複製(注意不要選擇到其他不相關的欄位，像是 id 等，才不會出錯)，再到剛剛import的頁面按 Ctrl + V 貼上 > [ Continue ] > 勾選 "Shot Code" Use as id  > [ Continue ] >  [ Finish and Import ]

---

### 指派工作 Assigned To / 多筆欄位一同修改 Edit Selected / 自訂篩選條件 Filter
![09](https://user-images.githubusercontent.com/42924265/75038624-afb5cc00-54f1-11ea-94d5-af491248e8a7.gif)

* 到目前專案的Shots頁面，於要指定工作的 **Assigned To** 欄位點選編輯，輸入關聯的人員名稱即可。可以一次選擇多筆欄位編輯填入相同內容。
* Shotgun幾乎 **「所有頁面」都有Filter** ，可以自訂需要的篩選條件，讓頁面顯示想要看的資訊，若目前頁面有篩選條件情況下， **篩選的「漏斗圖示」會呈現藍色**，若要清除篩選點選 **[ Clear All Filters]**。

---

### Project Timeline 所有專案時程表
![06](https://user-images.githubusercontent.com/42924265/75037124-6a43cf80-54ee-11ea-9cdf-3865b9668698.gif)

---
### Crew Planning 所有人員工作時程表
![07](https://user-images.githubusercontent.com/42924265/75037475-34ebb180-54ef-11ea-8cec-a01948cb490d.gif)

---
### Chart Page 自訂數據圖表
![08](https://user-images.githubusercontent.com/42924265/75037922-38cc0380-54f0-11ea-83f0-0a552339a89e.gif)

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



# 專家系統｜Expert Systems

111 學年度第二學期的 CLIPS 課程練習，涵蓋事實、規則、樣板、推論與規則優先順序。

國立彰化師範大學 · `1112_54021` · 授課教師：賴聯福 · [課程大綱](https://webapt.ncue.edu.tw/DEANV2/UploadDEAN/SUBJECT/1112/54021_1EICS2153630.pdf)


## 練習索引

| 主題 | 入口 |
| --- | --- |
| 汽車故障、親屬關係 | [car](0308_car.txt)、[parent](0315_parent.txt) |
| 排列、摩斯碼、排序 | [permutation](0322_permutation.txt)、[morse-code](0329_morse-code.txt)、[bubble-sort](0412_bubble-sort.txt) |
| 關係與銷售規則 | [relationship](0419_relationship.txt)、[sales](0426_sales) |
| 路徑、二元表示、繼承 | [path](0503_path_answer.txt)、[binary](0510_binary_answer.txt)、[inherit](0517_inherit) |
| 細胞、配對、錄取與工作 | [cell](0524_cell.txt)、[matching](0531_matching)、[admission](0607_admission.txt)、[job](0614_job.txt) |

共 34 份 `.txt`，包含練習、輸入資料、參考答案與輸出紀錄；各檔案用途請依名稱及內容判斷。

## 使用方式

安裝 CLIPS 後，將工作目錄切到儲存庫根目錄，再載入單一練習。例如汽車故障規則：

```clips
(clear)
(load "0308_car.txt")
(reset)
(assert (car-trouble (proublem noise-when-brake)))
(run)
```

`proublem` 是該檔案實際使用的欄位名稱。切換題目時先執行 `(clear)`，避免不同練習的規則相互影響。課堂題目及參考答案保留原有來源，未重新宣告統一授權。

# VitalLink 關係圖

以下是 VitalLink 智能馬桶的數據流：

```mermaid
graph TD
    A[Input: 用戶尿液數據<br>- pH 值: 4.5-8.0<br>- 蛋白質: <0.15 g/L<br>- 葡萄糖: <0.8 mmol/L]
    B[Input: 環境數據<br>- 溫度: 20-30°C<br>- 濕度: 40-70%]
    C[Input: 用戶背景<br>- 年齡: 25-80 歲<br>- 病史: 糖尿病 20%]
    D[VitalLink 智能馬桶<br>- 光譜分析: 95% 精準<br>- 殺菌: 99.9%]
    E[Process: AI 分析<br>- 異常檢測: 98%]
    F[Output: 病人端<br>- 早期發現率: +30%]
    G[Output: 醫療方<br>- 診斷效率: +20%]
    H[Output: 家人端<br>- 警訊: 100% 送達]
    A --> D
    B --> D
    C --> D
    D --> E
    E --> F
    E --> G
    E -->|緊急| H

2. **貼入編輯器**  
   - 在 `README.md` 或 `vital_link_diagram.md` 的編輯區域，貼入上述內容。
   - 如果是編輯 `README.md`，可以直接覆蓋原有內容，或在下方新增。

---

#### **步驟 4：提交變更**
1. **填寫提交訊息**  
   - 在頁面底部，找到「Commit changes」區域。
   - 在「Commit message」欄位輸入簡單描述，例如「Add VitalLink diagram」。

2. **提交**  
   - 點擊綠色的「Commit changes」按鈕。
   - 如果是新檔案，選擇「Create a new branch」或直接提交到主分支（預設 `main`）。

---

#### **步驟 5：檢查結果**
1. **返回儲存庫**  
   - 提交後，回到儲存庫主頁面。
   - 點擊 `README.md` 或 `vital_link_diagram.md` 查看。

2. **確認圖表**  
   - 您會看到標題「VitalLink 關係圖」，下方是一個流程圖，展示從輸入到輸出的數據流。
   - 如果圖表未正確顯示，可能是語法錯誤，請檢查是否有漏掉 ```mermaid 或多餘空格。

---

### 模擬畫面（文字版）
#### **編輯時**

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

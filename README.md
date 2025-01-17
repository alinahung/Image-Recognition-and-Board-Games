## 負責項目

1. **影像辨識訓練**
2. **手機 APP 的設計與開發**

## 軟體

1. **MIT App Inventor**（開發手機 APP）
2. **Personal Image Classifier (PIC) Tools**（影像辨識訓練）

## 硬體

1. Android 手機 * 1
2. 桌遊卡牌
3. 辨識區

## 實用功能描述

1. **登入介面、數據記錄與分析：**
   - 登入介面：系統將記錄玩家的資訊
   - 數據記錄與分析：遊戲數據和玩家決策將記錄在Google試算表中，便於後續的學習分析，幫助玩家總結經驗，提升學習效果。

2. **選擇災難編號**：
   - 每個回合對應一種災難，每種災難的發生機率、損害金額、保費都不同。

3. **保險決策模擬**：
   - 玩家需要根據風險發生的可能性來做出保險購買決策，購買決策分別為“不購買”“基礎保險”“進階保險”。

4. **影像辨識技術**：
   - 利用行動裝置上的攝像頭掃描卡牌，通過影像辨識技術自動識別卡牌上的資訊。

5. **即時反饋與動畫效果**：
   - 系統在辨識卡牌後會顯示相應的動畫或 GIF，並結合聲音、視覺效果等多媒體元素，模擬真實情境，增加遊戲的互動性與沉浸感。
     
6. **播放災難說明影片**：
   - 系統會根據災難的種類，播放相對應的避難說明影片，學生亦可根據自己的程度調整影片播放進度。

7. **問答刮刮樂**：
   - 依據災難說明影片，設計問答刮刮樂，如果答對會隨機加分（20、40、60、80、100），鼓勵學生觀看說明影片。

8. **成就系統**：
   - **銅級成就**：使用保險成功抵擋一次災難，獲得 50 分。
   - **銀級成就**：使用保險成功抵擋兩次災難，獲得 100 分。
   - **金級成就**：使用保險成功抵擋三次或以上災難，獲得 150 分
     
<img width="725" alt="截圖 2024-08-15 晚上10 24 45" src="https://github.com/user-attachments/assets/b04ae5e4-24e7-48d1-b57f-358bce583a60">

## 執行流程

**登入遊戲⭢選擇災難編號⭢保險購買⭢卡牌影像辨識⭢即時反饋⭢刮刮樂⭢檢視成就**
<br><br/>

## 遇到的問題與解決方式

- **問題**：辨識準確度低、過度擬合（overfitting）
- **解決方式**：
  - 設計辨識區（固定背景）
  - 增加樣本數與調整參數（如 Epochs、Training Data Fraction），提高辨識的準確度
<br><br/>
## 操作影片

https://github.com/user-attachments/assets/49075a73-a128-4ff3-827a-7bf251bfa472


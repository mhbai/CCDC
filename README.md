# 漢字落地挑戰 (CCDC)

## 說明

"漢字落地挑戰 (Chinese Character Drop Challenge, CCDC)" 是一款旨在幫助用戶練習中文打字技能的互動遊戲。漢字從屏幕頂部掉落，用戶必須正確輸入這些漢字以防止它們堆積在屏幕底部。隨著遊戲進行，漢字掉落的速度會逐漸增加，遊戲難度也會提升。本項目包括：

- 實現遊戲邏輯的 HTML5 文件。
- 美觀且易用的 CSS 樣式。
- 用於字符級別和概率的 JSON 數據。

## 特點

- **動態難度**：隨著漢字掉落速度的增加，遊戲變得更加具有挑戰性。
- **視覺反饋**：正確輸入的漢字會變色並漂浮消失。
- **美觀界面**：簡潔現代的用戶界面設計，提供引人入勝的使用體驗。

## 遊戲玩法

1. 克隆或下載此倉庫。
2. 在瀏覽器中打開 `index.html` 文件。
3. 在漢字掉落到屏幕底部之前正確輸入它們。
4. 正確輸入的漢字會漂浮消失。
5. 當底部堆積超過 10 個漢字時，遊戲結束。

## 文件

- `index.html`：包含遊戲的主 HTML 文件。
- `characters.json`：包含不同級別漢字數據的 JSON 文件。

## 開始使用

要開始使用，只需在瀏覽器中打開 `index.html` 文件。為了更好的體驗，建議使用本地 HTTP 伺服器。你可以使用 Python 啟動簡單的 HTTP 伺服器：

```bash
python -m http.server 8000

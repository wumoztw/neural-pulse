# Neural Pulse

Neural Pulse 是一款在瀏覽器中執行的文字冒險 / MUD 風格遊戲，背景設定在神經網路與電流交織的賽博世界中。玩家透過輸入指令來探索區域、互動事件並推進劇情。

## 功能特色

- 純前端實作：使用原生 **HTML**、**CSS**、**JavaScript**，無需後端即可直接在瀏覽器中遊玩。
- MUD 式指令操作：透過文字指令與世界互動（移動、觀察、使用能力等）。
- 持續狀態管理：遊戲會維護玩家當前位置、狀態與事件進度，根據輸入即時更新畫面。
- GitHub Pages 部署：可以直接透過 GitHub Pages 線上遊玩，或將專案下載到本機開啟。

## 線上遊玩

你可以直接在瀏覽器中遊玩 Neural Pulse（GitHub Pages）：

- 網址：<https://wumoztw.github.io/neural-pulse/>

## 專案結構

專案結構如下：

- `index.html`  
  - 網頁主框架，包含輸出訊息區、玩家輸入框以及基本 UI 元件。
- `style.css`  
  - 遊戲畫面的樣式與主題配色，例如終端機風格、深色背景與高對比字體。
- `game.js`  
  - 遊戲邏輯核心：
    - 初始化遊戲世界與玩家狀態
    - 解析玩家輸入的指令
    - 根據指令更新遊戲狀態與畫面輸出
    - 定義事件觸發、地圖節點與互動規則

## 安裝與執行

本專案為純前端專案，不需要額外的建置流程。

### 方式一：直接 clone 後開啟

```bash
git clone https://github.com/wumoztw/neural-pulse.git
cd neural-pulse

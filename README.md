# NCUE EE 2026 AI Class

國立彰化師範大學電機工程學系 AI 課程互動式學習平台

## 專案簡介

**AI Explorer v4.3** 是一個專為電機系學生設計的互動式 AI 學習平台，透過視覺化與參數調整，將抽象的 AI 概念連結到電機系必修數學，讓學生能直觀理解 AI 背後的數學原理。

## 核心特色

### 1. 數學與理論基礎

將 AI 概念回歸電機系數學本質：

- **線性代數**：互動式向量圖展示神經元的點積 (Dot Product) 與投影運算
- **信號與系統**：視覺化卷積 (Convolution) 操作，展示 Kernel 在圖片上的特徵提取（邊緣檢測）
- **機率與統計**：互動式 Spearman 相關係數計算，理解模型評估指標
- **前沿架構**：
  - Transformer：視覺化 Q × K^T 的 Self-Attention 機制
  - Mamba (SSM)：展示 Parallel Scan 的序列處理效率優化

### 2. 核心觀念 4.0

七大模組深度解析，搭配 Python 代碼對照（VS Code 風格語法高亮）：

- **感知器 (Perceptron)**：完全互動的單層神經網路，可手動調整權重 W 與偏差 b，觀察 ReLU 激活函數效果
- **電腦視覺 (CV)**：CNN、Autoencoder、GAN 對抗式生成網路
- **自然語言處理 (NLP)**：Teacher Forcing 訓練機制演示
- **大型語言模型 (LLM)**：Instruction Tuning 與 LoRA (Low-Rank Adaptation) 參數高效微調視覺化

### 3. AI 應用實驗室

結合電機系特色的實際應用：

- **電力負載與品質預測**：模擬太陽能板發電波動與 1F 超級電容的平滑控制策略
- **多模態情感辨識**：基於 Valence-Arousal 座標系的情緒分析，展示對角矩陣與軟標籤應用

## 技術架構

採用**單一檔案 (Single-File Component)** 架構設計，極輕量化且易於部署：

- **前端框架**: React 18 (via CDN)
- **樣式系統**: Tailwind CSS (via CDN)
- **編譯器**: Babel Standalone
- **圖示**: Lucide React (SVG)
- **視覺化**: Custom SVG & CSS Animations（無外部圖表庫依賴）

## 快速開始

### 方式一：線上瀏覽
訪問 Live Demo：[https://ncue-ee-2026-ai-class.vercel.app/]

### 方式二：本地運行

由於採用單一 HTML 架構，只需下載 `index.html` 即可運行：

```bash
# Clone 專案
git clone https://github.com/brian10420/NCUE_EE_2026_AI_Class.git

# 進入目錄
cd NCUE_EE_2026_AI_Class

# 直接用瀏覽器打開
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

無需安裝任何依賴，所有資源透過 CDN 載入。

## 專案結構

```
NCUE_EE_2026_AI_Class/
├── index.html           # 主要應用檔案（包含所有邏輯）
├── README.md           # 專案說明
└── LICENSE             # MIT 授權
```

所有互動邏輯封裝在 `index.html` 的 `<script type="text/babel">` 標籤內。

## 使用說明

1. 開啟 `index.html` 後，選擇學習模組
2. 調整參數滑桿觀察即時變化
3. 對照 Python 代碼理解實作細節
4. 透過波形與矩陣視覺化掌握數學原理

## 貢獻指南

本專案是開源教育資源，歡迎貢獻：

- 提交 Issue 回報問題或建議新功能
- 提交 Pull Request 增加新的電機 × AI 實驗模組
- 改進現有視覺化效果或說明文字

## 版本更新

### v4.3 (Fixed)
- 修復已知問題
- 優化互動體驗
- 改進視覺化效能

## 授權

MIT License - 本專案為 NCUE EE 教育用途創建

## 聯絡方式

- 專案維護: [@brian10420](https://github.com/brian10420)
- 問題回報: [GitHub Issues](https://github.com/brian10420/NCUE_EE_2026_AI_Class/issues)

---

**Connecting Electrical Engineering with Artificial Intelligence**
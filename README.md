# NCUE_EE_2026_AI_Class
學生可以透過調整參數、觀察波形與矩陣變化，直觀理解 AI 背後的數學原理。
1. 數學與理論基礎 (Math Foundations)
將抽象的 AI 概念連結回電機系必修數學：
線性代數：透過互動式向量圖，展示神經元運作本質即為「點積 (Dot Product)」與「投影」。
信號與系統：視覺化 卷積 (Convolution) 操作，展示 Kernel 如何在圖片上滑動以提取特徵（如邊緣檢測）。
機率與統計：互動式 Spearman 相關係數 計算，理解模型評估指標。
前沿架構：
Transformer：視覺化 $Q \times K^T$ 的 Self-Attention 機制。
Mamba (SSM)：展示 Parallel Scan 操作如何解決序列處理效率問題。
2. 核心觀念 4.0 (Interactive Concepts)
包含七大模組的深度解析與 Python 代碼對照（支援 VS Code 風格高亮）：
感知器 (Perceptron)：完全互動的單層神經網路，可手動調整 $W$ 與 $b$，觀察 ReLU 激活函數的截斷效果。
電腦視覺 (CV)：CNN、Autoencoder、GAN 對抗式生成網路。
自然語言處理 (NLP)：Teacher Forcing 訓練機制演示。
大型語言模型 (LLM)：Instruction Tuning 與 LoRA (Low-Rank Adaptation) 參數高效微調的可視化。
3. 人工智慧應用實驗室 (AI Lab)
結合電機系特色的實際應用場景：
⚡ 電力負載與品質預測：模擬 太陽能板 發電波動與 1F 超級電容 的平滑控制策略。
❤️ 多模態情感辨識：基於 Valence-Arousal 座標系的情緒分析，展示對角矩陣 (Diagonal Matrix) 與軟標籤 (Soft Label) 的應用。
 技術棧 (Tech Stack)
本專案採用 單一檔案 (Single-File Component) 架構設計，極輕量化且易於部署。
Frontend Framework: React 18 (via CDN)
Styling: Tailwind CSS (via CDN)
Compiler: Babel (Standalone)
Icons: Lucide React (SVG implementation)
Charts/Visuals: Custom SVG & CSS Animations (No external heavy charting libraries)
🚀 快速開始 (Quick Start)
方式一：直接瀏覽
點擊 Live Demo 直接開始探索。
方式二：本地運行
由於是單一 HTML 架構，您只需要下載 index.html 即可運行。
Clone 此專案：
git clone [https://github.com/your-username/NCUE_EE_2026_AI_Class.git](https://github.com/your-username/NCUE_EE_2026_AI_Class.git)


直接用瀏覽器打開 index.html。
 貢獻與開發
本專案是一個開源教育資源。
所有的互動邏輯都封裝在 index.html 的 <script type="text/babel"> 標籤內。
歡迎提交 Pull Request 增加新的電機 x AI 實驗模組。
 License
MIT License. Created for educational purposes at NCUE EE.

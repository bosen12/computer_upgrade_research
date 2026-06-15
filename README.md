<div align="center">

# 🖥️ PC 升級分析 · 三版 AI 報告比較

**同一份升級需求** — `i5-12400 + RTX 4060 Ti 8G` → `R7 7700 + RTX 5070 Ti 16G`（原價屋估價單，NT$ 83,458）
**三個 AI** 各自產出一份分析報告。本專案閱讀比較三者，並把每一版都製作成精美的 HTML / PDF。

![Build](https://img.shields.io/badge/Build-AMD_AM5-orange?style=flat-square)
![GPU](https://img.shields.io/badge/GPU-RTX_5070_Ti_16G-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Price](https://img.shields.io/badge/NT$-83,458-blue?style=flat-square)

</div>

---

## 📊 哪一份寫得好？（品質評比）

| 版本 | 風格定位 | 優點 | 缺點 | 評價 |
|------|---------|------|------|------|
| **Claude Opus 4.8** | 深度技術版 | 最完整、最準確、最平衡；含完整規格/價格表、LLM/VLM 模型表、省錢建議與評分；誠實點出 1080p CPU 瓶頸與 MPK 保固陷阱；AI 加速估計合理（1.7–2.5×） | 篇幅最長 | 🥇 **最佳** |
| **Gemini Pro** | 視覺豐富版 | 可讀性最強、分段生動、品牌梯隊講解清楚 | 行銷誇飾、部分數據誇大（宣稱 Z-Image 提升 20×、0.05 s/it，屬理想峰值） | 🥈 好看但需修數據 |
| **ChatGPT** | 簡潔清爽版 | 最精簡、好瀏覽、抓重點快 | 內容最單薄、缺價格依據；原有一處小錯（已修正：12400→7700 為 +4 執行緒非 +8） | 🥉 快速參考 |

> **結論**：論內容深度與正確性，**Claude Opus 版最扎實**；要快速吸睛選 Gemini（但別盡信其倍率）；只想快速掃過選 ChatGPT。

---

## 📁 專案結構

| 版本 | 原始報告 | 精美 HTML | PDF |
|------|---------|-----------|-----|
| ◆ Claude Opus 4.8 | [`readme.md`](claude%20opus%204.8%20high/readme.md) | [`report.html`](claude%20opus%204.8%20high/report.html) | [`report.pdf`](claude%20opus%204.8%20high/report.pdf) |
| ✦ Gemini Pro | [`README.md`](gemini%20pro/README.md) | [`report.html`](gemini%20pro/report.html) | [`report.pdf`](gemini%20pro/report.pdf) |
| ◇ ChatGPT | [`readme.md`](chatgpt/readme.md) | [`report.html`](chatgpt/report.html) | [`report.pdf`](chatgpt/report.pdf) |

每個 HTML 都是**自包含**（內嵌 CSS 與 SVG，可直接用瀏覽器開啟、離線可看），並各有獨立配色：Claude＝暗色工程感、Gemini＝漸層活潑、ChatGPT＝清爽綠。

---

## 🖼️ 關於產品圖片

由你提供官方產品照後，已全部接上（逐一核對型號，無張冠李戴）：

| 零件 | 圖片 | 來源 |
|------|------|------|
| 🎮 顯示卡 技嘉 RTX 5070 Ti GAMING OC | [`5070ti.png`](assets/images/5070ti.png) | ✅ 真實產品照 |
| 🧩 主機板 技嘉 B850 AORUS STEALTH | [`b850.png`](assets/images/b850.png) | ✅ 真實產品照 |
| 💾 記憶體 Biwin Black Opal DW100 | [`1-biwin-dw100-memory-black-1.webp`](assets/images/1-biwin-dw100-memory-black-1.webp) | ✅ 真實產品照 |
| 🗄️ 機殼 全漢 M580 PRO-BA | [`m580pro.jpg`](assets/images/m580pro.jpg) | ✅ 真實產品照 |
| 🖥️ 整機封面 | [`build-render-rgb.jpg`](assets/images/build-render-rgb.jpg) ／ [`build-render-white.jpg`](assets/images/build-render-white.jpg) | 🎨 AI 生成示意圖 |
| CPU / SSD / 水冷 / 電源 | — | 🧩 精確標註之 SVG 向量圖 |

> 🎨 整機封面圖為 AI 生成示意圖，已標明；CPU、SSD、水冷、電源未提供實照，維持精確 SVG。若補上實照，丟進 [`assets/images/`](assets/images/) 我可再接上並重出 PDF。

---

<div align="center">
<sub>三 AI 報告比較專案 · 生成於 2026-06-15 · 數據為估算，實際以評測為準</sub>
</div>

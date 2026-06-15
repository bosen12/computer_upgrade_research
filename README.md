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

## 🖼️ 關於產品圖片（混合策略）

- 🎮 **顯示卡**：採用**真實照片**（[`assets/images/gpu-rtx5070ti.jpg`](assets/images/gpu-rtx5070ti.jpg)，來源 TechPowerUp，1200×594）。為 RTX 5070 Ti **公版示意**，實品為技嘉三風扇 GAMING OC，已於圖說標明。
- 🧩 **其餘零件**：採用**精美 SVG 向量示意圖**，以**精確型號標註**（CPU / 主機板 / 記憶體 / SSD / 水冷 / 機殼 / 電源）。

> ⚠️ 為什麼不是全部真實照？確切型號的官方照都在會封鎖此環境的網站上（Gigabyte / DuckDuckGo 回 403、Bing 無 JS 退化）。能穩定下載的只有同類代表照或公版照——為避免把「別的型號」當成你的零件（即「搞混」），其餘維持精確 SVG。
> 👉 若你有官方產品照，放進 [`assets/images/`](assets/images/) 並以零件命名即可無痛替換，我可再幫你接上並重出 PDF。

---

<div align="center">
<sub>三 AI 報告比較專案 · 生成於 2026-06-15 · 數據為估算，實際以評測為準</sub>
</div>

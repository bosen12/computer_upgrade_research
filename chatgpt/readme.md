<div align="center">

# 🖥️ 12400 + RTX 4060 Ti → R7 7700 + RTX 5070 Ti 升級分析

**◇ ChatGPT · 簡潔清爽版**

![CPU](https://img.shields.io/badge/CPU-Ryzen_7_7700-ED1C24?style=for-the-badge&logo=amd&logoColor=white)
![GPU](https://img.shields.io/badge/GPU-RTX_5070_Ti_16G-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![RAM](https://img.shields.io/badge/RAM-48GB_DDR5--6000_CL28-7A5CFF?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-AMD_AM5-orange?style=for-the-badge)

📄 另有精美版本：[**HTML 報告**](report.html) ｜ [**PDF 報告**](report.pdf)

</div>

---

> **目前配備** - CPU：Intel Core i5-12400 - GPU：RTX 4060 Ti 8GB -
> RAM：DDR4 32GB (16×2) - 主機板：MSI PRO B760M-A WIFI DDR4 -
> SSD：Micron P5 Plus 1TB - 電源：650W

> **升級菜單** - AMD Ryzen 7 7700 - Gigabyte B850 AORUS STEALTH - Biwin
> Black Opal DW100 DDR5-6000 CL28 48GB (24×2) - ZhiTai TiPro9000 1TB -
> ID-Cooling FX360 - Gigabyte RTX 5070 Ti Gaming OC 16GB - Montech M580
> PRO - MSI MPG A850GS PCIe5 850W

------------------------------------------------------------------------

# 1. 各零件分析

## CPU：Ryzen 7 7700

-   8C16T，比12400多2核心4執行緒
-   多工、AI、生圖、背景程式提升明顯
-   遊戲平均提升約15\~30%，CPU密集遊戲更高

## 主機板：B850 AORUS STEALTH

優點： - 14+2+2相供電 - 5GbE + WiFi 7 - PCIe 5.0 - 未來可升級Zen5/Zen6

### B850 三大品牌比較

  品牌                     定位     供電       特色             價格
  ------------------------ -------- ---------- ---------------- --------------
  Gigabyte AORUS STEALTH   高階     14+2+2     5GbE、散熱最好   約7900
  MSI Tomahawk             中高階   14相左右   BIOS成熟         約7000\~8000
  ASUS TUF B850            中階     12\~14相   耐用             約6500\~7500
  ASUS ROG Strix           高階     16相以上   功能最多         9000以上

------------------------------------------------------------------------

## 顯示卡：RTX 5070 Ti Gaming OC

### 三大品牌比較

  品牌                 等級     散熱              價格
  -------------------- -------- ----------------- ----------------
  Gigabyte Gaming OC   中高階   Windforce三風扇   約36990
  MSI Gaming Trio      中高階   Tri Frozr         約37000\~39000
  ASUS TUF             高階     超大散熱          39000左右
  ASUS ROG Strix       旗艦     最佳散熱、超頻    42000以上

Gaming OC
屬於CP值很高的一級產品，與ROG相比效能通常只差1\~3%，主要差異在散熱、噪音與用料。

------------------------------------------------------------------------

## 記憶體

DDR5-6000 CL28 48GB - 延遲低 - AI、生圖、大型城市模擬遊戲比DDR4更有利 -
48GB足夠多工

------------------------------------------------------------------------

## SSD

TiPro9000 - 約14GB/s讀取 - 載入大型模型速度提升 - 生圖載入Checkpoint較快

------------------------------------------------------------------------

# 2. 1080P 遊戲分析

  遊戲                 目前           升級後          提升
  -------------------- -------------- --------------- ------------------
  3A大作 Ultra         100\~140 FPS   180\~260 FPS    約60\~90%
  VALORANT             350\~450 FPS   500\~700 FPS    CPU提升約30%以上
  Cities Skylines II   CPU限制明顯    約25\~45%提升   大型城市改善最多

1080P下： - 多數3A開始偏CPU瓶頸 - Ryzen 7700足以發揮5070Ti大部分性能 -
若追求極高FPS，可再升級9800X3D等X3D平台

------------------------------------------------------------------------

# 3. AI 生圖

目前：

-   Z Image Turbo：約2 s/it
-   Illustrious XL：約2 it/s

理論升級：

GPU算力約提升80\~100%

推估：

  模型             目前     升級
  ---------------- -------- ---------------
  Z Image Turbo    2 s/it   約1\~1.2 s/it
  Illustrious XL   2 it/s   3.5\~4.2 it/s

CPU提升可降低資料前處理等待時間，多工時更明顯。

------------------------------------------------------------------------

# 4. 可使用模型

16GB VRAM 可嘗試：

-   FLUX Dev
-   FLUX Schnell
-   SDXL
-   Illustrious XL
-   Pony XL
-   Juggernaut XL
-   Wan Video部分流程
-   Qwen 7B FP4
-   Gemma 3 12B量化
-   Mistral Small量化

比8GB VRAM能使用更多ControlNet、LoRA與高解析工作流程。

------------------------------------------------------------------------

# 5. AI Toolkit 訓練 LoRA

可以。

16GB VRAM：

-   SDXL LoRA
-   Pony XL LoRA
-   Illustrious XL LoRA
-   FLUX LoRA（降低batch及解析度）

均可訓練，只是FLUX速度仍會比24GB顯卡慢。

------------------------------------------------------------------------

# 6. 多工能力

你平常： - ComfyUI - 三個以上機器人 - 瀏覽器 - Discord - 其他背景程式

48GB RAM +
8核心16緒能大幅降低背景程式互相搶資源的情況，體驗會比目前平台流暢許多。

------------------------------------------------------------------------

# 總結

整體屬於跨世代升級。

-   遊戲：約60\~90% GPU提升
-   CPU多工：約40\~70%
-   AI生圖：約80\~100%
-   可用模型增加非常多
-   可以開始使用AI Toolkit訓練LoRA
-   未來AM5平台仍有升級空間

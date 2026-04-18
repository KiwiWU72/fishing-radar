# 🎣 Jiādōng Wild Pond · Tactical Fishing Intelligence System (v4.0)
### 🌊 佳冬野生池 · 實戰釣魚戰術儀表板

A high-precision tactical dashboard designed for estuarine wild ponds in Jiadong, Pingtung. This system replaces empirical guesswork with **CWA real-time data** and models "Bite Windows" based on fundamental hydrological and biological mechanisms.

這是一個專為屏東佳冬「感潮型野生池」設計的高精度戰術儀表板。本系統屏棄模糊的經驗法則，改以**中央氣象署 (CWA) 實時數據**為基礎，透過水文學與生物學的底層機制對「魚口開啟」時窗進行建模。

---

## 🔬 Scientific Framework (First Principles) | 科學架構（第一性原理）

The system prioritizes extreme bottom-layer mechanism testing over "marketing talk," focusing on the essence of biological and physical interactions:
本系統優先考慮最底層的機制檢視，而非行銷語言，專注於生物與物理交互作用的本質：

* **Rheotaxis Trigger (Fluid Dynamics)** | **趨流性觸發（流體力學）**:
    * **Mechanism**: Estuarine species respond to flow velocity peaks. Tidal differences trigger fish mechanoreceptors at specific velocity thresholds (10–30 cm/s).
    * **機制**: 感潮魚類對流速峰值有反應。潮差在特定流速閾值（10-30 cm/s）時會觸發魚類的側線機械感受器。
    * **Calibration**: Includes a **1.5-hour delay** to account for Jiadong’s specific geomorphological tide lag.
    * **校正**: 包含 **1.5 小時延遲**，以補償佳冬特定地形的潮汐滯後。

* **Q10 Metabolic Effect (Thermodynamics)** | **Q10 代謝效應（熱力學）**:
    * **Mechanism**: Fish metabolic rates (Q10 ≈ 2) double with every 10°C rise. The system evaluates current water temp against species-specific $T_{opt}$ (Optimal Temperature).
    * **機制**: 魚類代謝率（Q10 ≈ 2）每上升 10°C 約增加一倍。系統根據物種特定的 $T_{opt}$（最適溫度）評估當前水溫。

* **Dissolved Oxygen (DO) Gradients** | **溶氧量 (DO) 梯度**:
    * **Mechanism**: Models the interaction between photosynthesis-driven oxygen peaks (late afternoon) and nighttime hypoxia dips to predict predatory bursts.
    * **機制**: 模擬光合作用驅動的溶氧峰值（傍晚）與夜間缺氧谷值之間的交互作用，預測掠食爆發期。

---

## 🛠️ Technical Features | 技術特點

* **CWA API Integration**: Real-time updates for wind speed, temperature, and precipitation.
    * **CWA API 整合**: 實時更新風速、氣溫與降雨數據。
* **Dynamic Fish Tank (Canvas v2)**: Behavioral simulation based on current activity index.
    * **動態魚池**: 基於當前活性指數進行魚群行為模擬。
* **Golden Timeline**: Automated scanning for "Rising 70%" and "Falling 30%" fluid velocity windows.
    * **黃金時窗**: 自動掃描「漲七分」與「退三分」的流速視窗。
* **Gear & Bait Logic**: Dynamic recommendations based on current fluid shear stress and species behavior.
    * **釣組策略**: 根據當前流體切應力與魚種行為給予動態建議。

---

## 🚀 Getting Started | 快速開始

1.  **API Key**: Obtain a free key from [CWA Open Data Platform](https://opendata.cwa.gov.tw).
    * **API 金鑰**: 前往 [中央氣象署開放資料平台](https://opendata.cwa.gov.tw) 免費申請。
2.  **Configuration**: Click the ⚙️ icon to set your Key and **Phase Delay (1.5h Recommended)**.
    * **系統設定**: 點擊 ⚙️ 圖示輸入 Key 並設置 **潮汐延遲（建議 1.5h）**。
3.  **Deployment**: Pure HTML/JS. Compatible with GitHub Pages.
    * **部署**: 純 HTML/JS 架構，完全相容 GitHub Pages。

---

## 📊 Data Source | 數據來源

* **Hydrology & Weather**: Central Weather Administration (CWA).
* **Solar Equations**: NOAA simplified solar calculations for Sunrise/Sunset.
* **Biology**: Euryhaline species biomechanics and metabolic research.

---

> **"In God we trust, all others must bring data."**
> **「除了上帝，所有人都必須帶著數據過來。」**

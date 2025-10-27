
# 📘 **Project Summary / 專案摘要**

### Macro Sensitivity Analysis of UK & European Banking Stocks (2020 – 2025)

---

## 🎯 **Objective / 研究目的**

**EN:**
To quantify how UK and European bank equities react to macroeconomic factors — specifically interest rate changes and FX movements (GBP/USD).
The goal is to identify which banks benefit the most from a rising rate environment and how exchange rate fluctuations affect their returns.

**中文：**
分析英國與歐洲主要銀行股對宏觀變數（特別是利率與英鎊匯率）變化的敏感度，
找出在升息環境中最受惠的銀行，以及匯率波動對股價報酬的影響。

---

## ⚙️ **Methodology / 研究方法**

**EN:**

* **Data Source:** Yahoo Finance daily closing prices from 2020 to 2025.
* **Variables:**
  Dependent – daily stock returns of six major banks (Barclays, HSBC, Lloyds, NatWest, Deutsche Bank, BNP Paribas).
  Independent – daily changes in 10-year Treasury yield (^TNX) and GBP/USD exchange rate.
* **Model:** Ordinary Least Squares (OLS) regression using Python (pandas, statsmodels).
* **Visualization:** Seaborn heatmaps and regression plots for β coefficients and rate-return relationships.

**中文：**

* **資料來源：** Yahoo Finance 每日收盤價（2020–2025）。
* **變數設定：**
  應變數為六家主要英歐銀行的每日報酬率；
  自變數為 10 年期美債殖利率 (^TNX) 及 英鎊兌美元 (GBP/USD) 每日變化。
* **模型：** 以 OLS 迴歸法估計利率 β 與 匯率 β。
* **視覺化：** 利用 Seaborn 繪製 Heatmap 及 回歸散點圖以呈現關係。

---

## 📊 **Key Findings / 主要結果**

**EN:**

1. **Positive Rate Sensitivity:** Barclays and Lloyds exhibit the highest positive β to interest rates (~0.19–0.20), confirming they benefit most from rate hikes.
2. **FX Exposure:** HSBC shows a negative FX β (≈ -0.14), reflecting the impact of GBP appreciation on its USD-denominated earnings.
3. **Continental Banks:** BNP Paribas and Deutsche Bank have similar rate exposure (β≈ 0.21), but lower correlation with GBP/USD, indicating Eurozone diversification.

**中文：**

1. **利率敏感性：** Barclays 與 Lloyds 的 β 約 0.19–0.20，對利率上升反應最強，
     顯示其在升息循環中獲利能力明顯提升。
2. **匯率曝險：** HSBC 匯率 β 為 -0.14，顯示英鎊升值會壓縮其美元收入。
3. **歐洲銀行：** BNP 與 Deutsche Bank 利率 β 約 0.21，對歐元區利率變化仍具敏感度，
     但與英鎊匯率關聯性較低，代表業務多元化。

---

## 🧠 **Interpretation / 結果解讀**

**EN:**

* UK domestic banks are clearly rate-driven; their returns move in tandem with long-term yields.
* HSBC’s negative FX exposure highlights its global revenue structure.
* Overall, the findings mirror post-COVID monetary policy cycles (BoE vs ECB).

**中文：**

* 英國本土銀行的股價明顯受利率驅動。
* HSBC 因國際業務占比高，呈現與匯率反向的走勢。
* 整體趨勢與疫情後 BoE 與 ECB 的貨幣政策路徑相符。

---

## 📈 **Visual Highlights / 視覺成果**

**EN:**

1. **Normalized Stock Performance Chart** – Shows long-term divergence among UK and EU banks.
2. **Macro Beta Heatmap** – Visualizes interest rate and FX betas across banks.
3. **Regression Plot** – Demonstrates Barclays’ positive relationship with 10-year yield changes.

**中文：**

1. **股價標準化趨勢圖：** 呈現英歐銀行長期表現差異。
2. **宏觀 β 熱力圖：** 顯示各銀行對利率與匯率的敏感度。
3. **回歸圖：** Barclays 股價與 10 年期利率呈顯著正相關。

---

## 🧾 **Conclusion & Implications / 結論與啟示**

**EN:**

* Rate-sensitive UK banks stand to gain most from a “higher-for-longer” environment.
* FX movements pose divergent impacts on international vs domestic banks.
* This analysis demonstrates how macro variables can be quantitatively linked to equity performance — a key skill for Equity Research and Sales & Trading roles.

**中文：**

* 對利率敏感的英國銀行將在「長期高利率」環境中持續受益。
* 匯率波動對跨國銀行與本土銀行的影響方向不同。
* 本研究展示如何以量化方法將宏觀經濟變數與股票表現連結，
   這正是 Equity Research 與 Sales & Trading 部門的重要能力。

---

## 💼 **Skills Demonstrated / 展示能力**

**EN:** Python (pandas, statsmodels, seaborn), Data Cleaning & Visualization, Financial Modeling, Regression Analysis, Macroeconomic Interpretation.
**中文：** Python 金融資料分析、資料清理與視覺化、財務建模、迴歸分析、宏觀經濟解讀。


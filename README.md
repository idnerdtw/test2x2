# Test2x2 - Statistical Calculator

An easy-to-use Android app for calculating Fisher's exact test, chi-square test, and diagnostic statistics from 2×2 contingency tables.

[繁體中文說明](#繁體中文說明) | [English](#english)

## English

### 🔗 Links
- **Download**: [Google Play Store](https://play.google.com/store/apps/details?id=com.idnerdtw.test2x2)
- **Website**: https://idnerd.github.io/test2x2/
- **Privacy Policy**: https://idnerd.github.io/test2x2/privacy.html

### 📊 Features
- Fisher's exact test
- Chi-square test  
- Sensitivity & Specificity
- Positive Predictive Value (PPV)
- Negative Predictive Value (NPV)
- Diagnostic Odds Ratio
- 95% Confidence Intervals for all calculations

### 📖 Development Story

Test2x2 has an interesting development journey spanning over a decade:

#### 2010 - aStat Origins
Originally developed as ["aStat"](https://idnote.blogspot.com/2010/11/astat.html) when smartphones were just emerging. The HTC Desire was popular, and Android API was at level 4. The tool was designed for convenient calculation of 2×2 contingency table statistics, NNT/NNH, and confidence intervals for proportions.

#### 2020-2024 - Dormancy Period
aStat became outdated due to lack of maintenance. Many technical specifications (such as privacy policies) were left incomplete, leading to removal from Google Play Store in 2022.

#### 2025 - AI-Assisted Revival
Using LLM tools (including Claude AI), the project was revived as a React prototype on a0.dev platform, then transformed into a native Android app with Kotlin. We discovered that "aStat" was already being used by multiple companies and software products. To avoid legal issues, we rebranded and focused specifically on **2×2 contingency table analysis**, releasing it as Test2x2.

### 🚀 Future Plans

Test2x2 focuses solely on 2×2 contingency table analysis. The original aStat had additional features that we plan to develop as separate specialized apps:

- **PersonTime Calculator**: Person-time statistical inference and incidence rate comparisons
- **NNT/NNH Calculator**: Number Needed to Treat/Harm with Newcombe's method confidence intervals  
- **Proportion CI Calculator**: Single proportion confidence intervals using Exact, Wilson's score, and Agresti-Coull methods

### 🛠️ Technical Details
- **Platform**: Native Android
- **Language**: Kotlin
- **IDE**: Android Studio
- **Calculations**: Local computation, no internet required
- **Privacy**: No data collection

### ⚠️ Important Disclaimer
This app is for **educational purposes only**. Results should be validated using professional statistical software (R, SPSS, SAS) before publication or clinical use.

### 📁 Repository Structure
- `/` - Project website and privacy policy (GitHub Pages)
- `/src/` - Kotlin source code and technical documentation
- `/screenshots/` - App screenshots for website

### 📧 Contact
- **Email**: test2x2app@gmail.com
- **Issues**: [GitHub Issues](https://github.com/idnerd/test2x2/issues)

### 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### 🙏 Acknowledgments
- Original aStat (2010) - The foundation that inspired this revival
- [a0.dev](https://a0.dev) - For rapid prototyping capabilities  
- Claude AI - For development assistance and code conversion
- Android community - For excellent documentation and examples

**Postscript**: During the rewrite process, I discovered that confidence interval estimation methods like Wilson's score (which required reading research papers and finding code back in the day) are now standard practice in R. We hope you enjoy this modern revival of a classic little tool! 🎉

---

## 繁體中文說明

用於計算 2×2 列聯表的費雪精確檢定、卡方檢定及診斷統計的易用 Android 應用程式。

### 🔗 連結
- **下載**: [Google Play 商店](https://play.google.com/store/apps/details?id=com.idnerdtw.test2x2)
- **網站**: https://idnerd.github.io/test2x2/
- **隱私權政策**: https://idnerd.github.io/test2x2/privacy.html

### 📊 功能特色
- 費雪精確檢定
- 卡方檢定
- 敏感度與特異度
- 陽性預測值 (PPV)
- 陰性預測值 (NPV)
- 診斷勝算比
- 所有計算的 95% 信賴區間

### 📖 開發故事

Test2x2 有一個橫跨十多年的有趣開發歷程：

#### 2010 - aStat 起源
最初以 ["aStat"](https://idnote.blogspot.com/2010/11/astat.html) 為名開發，當時智慧型手機剛剛興起。HTC Desire 紅極一時，Android API 也還在第四版。這個工具主要是方便計算 2×2 列聯表相關統計量、NNT/NNH、比例的信賴區間估計等。

#### 2020-2024 - 沉寂歲月
aStat 因缺乏維護而逐漸過時。許多細節規範（如隱私權）未能完成，最終導致 2022 年從 Google Play Store 下架。

#### 2025 - AI 輔助重寫與重新命名
利用 LLM 工具（包括 Claude AI）重新啟動專案，先在 a0.dev 平台開發 React 原型，再轉換為 Kotlin 原生 Android 應用程式。發現「aStat」這個名稱已經被多家不同的公司和統計軟體產品使用。為了避免潛在的法律問題，我們決定重新命名並專注於 **2×2 列聯表分析**，以 Test2x2 重新上架。

### 🚀 未來開發計劃

Test2x2 專注於 2×2 列聯表分析。原始 aStat 的其他統計功能，我們計劃開發為獨立的專門應用程式：

- **人年計算器**: 人年統計推論，比較暴露與非暴露組別的發生率
- **NNT/NNH 計算器**: 治療所需人數/傷害所需人數計算，使用 Newcombe 方法提供信賴區間
- **比例信賴區間計算器**: 使用精確方法、Wilson's score 方法、Agresti-Coull 方法計算單一比例的信賴區間

### 🛠️ 技術詳情
- **平台**: 原生 Android
- **語言**: Kotlin
- **開發環境**: Android Studio
- **計算**: 本地運算，無需網路
- **隱私**: 不收集資料

### ⚠️ 重要免責聲明
本應用程式**僅供教育使用**。在發表或臨床使用前，請使用專業統計軟體（R、SPSS、SAS）驗證結果。

### 📁 儲存庫結構
- `/` - 專案網站和隱私權政策 (GitHub Pages)
- `/src/` - Kotlin 原始碼和技術文件
- `/screenshots/` - 網站用應用程式截圖

### 📧 聯絡方式
- **電子郵件**: test2x2app@gmail.com
- **問題回報**: [GitHub Issues](https://github.com/idnerd/test2x2/issues)

### 📜 授權
本專案採用 MIT 授權 - 詳見 [LICENSE](LICENSE) 檔案。

### 🙏 致謝
- 原始 aStat (2010) - 啟發這次復活的基礎
- [a0.dev](https://a0.dev) - 提供快速原型開發能力
- Claude AI - 開發協助和程式碼轉換
- Android 社群 - 提供優秀的文件和範例

**後記**: 在改寫的過程發現，關於比例的信賴區間的估計，當年需要讀論文找程式碼的區間估計Wilson's score method，如今已是R的標準作法了。希望大家喜歡這個小工具的現代復活版本！🎉

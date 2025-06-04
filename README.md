# Test2x2 - Statistical Calculator

An easy-to-use Android app for calculating Fisher's exact test, chi-square test, and diagnostic statistics from 2×2 contingency tables.

## 🔗 Links
- **Download**: [Google Play Store](https://play.google.com/store/apps/details?id=com.idnerdtw.test2x2)
- **Website**: https://idnerd.github.io/test2x2/
- **Privacy Policy**: https://idnerd.github.io/test2x2/privacy.html

## 📊 Features
- Fisher's exact test
- Chi-square test  
- Sensitivity & Specificity
- Positive Predictive Value (PPV)
- Negative Predictive Value (NPV)
- Diagnostic Odds Ratio
- 95% Confidence Intervals for all calculations

## 📖 Development Story

Test2x2 has an interesting development journey spanning over a decade:

### 2010 - aStat Origins
Originally developed as ["aStat"](https://idnote.blogspot.com/2010/11/astat.html) when smartphones were just emerging. The HTC Desire was popular, and Android API was at level 4. The tool was designed for convenient calculation of 2×2 contingency table statistics, NNT/NNH, and confidence intervals for proportions.

### 2020-2024 - Dormancy Period
aStat became outdated due to lack of maintenance. Many technical specifications (such as privacy policies) were left incomplete, leading to removal from Google Play Store in 2022.

### 2025 - AI-Assisted Revival
Using LLM tools (including Claude AI), the project was revived as a React prototype on a0.dev platform, then transformed into a native Android app with Kotlin. We discovered that "aStat" was already being used by multiple companies and software products. To avoid legal issues, we rebranded and focused specifically on **2×2 contingency table analysis**, releasing it as Test2x2.

## 🚀 Future Plans

Test2x2 focuses solely on 2×2 contingency table analysis. The original aStat had additional features that we plan to develop as separate specialized apps:

- **PersonTime Calculator**: Person-time statistical inference and incidence rate comparisons
- **NNT/NNH Calculator**: Number Needed to Treat/Harm with Newcombe's method confidence intervals  
- **Proportion CI Calculator**: Single proportion confidence intervals using Exact, Wilson's score, and Agresti-Coull methods

## 🛠️ Technical Details
- **Platform**: Native Android
- **Language**: Kotlin
- **IDE**: Android Studio
- **Calculations**: Local computation, no internet required
- **Privacy**: No data collection

## ⚠️ Important Disclaimer
This app is for **educational purposes only**. Results should be validated using professional statistical software (R, SPSS, SAS) before publication or clinical use.

## 📁 Repository Structure
- `/` - Project website and privacy policy (GitHub Pages)
- `/src/` - Kotlin source code and technical documentation
- `/screenshots/` - App screenshots for website

## 📧 Contact
- **Email**: test2x2app@gmail.com
- **Issues**: [GitHub Issues](https://github.com/idnerd/test2x2/issues)

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments
- Original aStat (2010) - The foundation that inspired this revival
- [a0.dev](https://a0.dev) - For rapid prototyping capabilities  
- Claude AI - For development assistance and code conversion
- Android community - For excellent documentation and examples

---

**Postscript**: During the rewrite process, I discovered that confidence interval estimation methods like Wilson's score (which required reading research papers and finding code back in the day) are now standard practice in R. We hope you enjoy this modern revival of a classic little tool! 🎉

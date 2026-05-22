# German Credit Risk Assessment using Machine Learning

Ushbu loyiha bank mijozlarining kredit riskini (yaxshi yoki yomon kredit riski) aniqlash va tasniflash uchun tayyorlangan. Loyihada ma'lumotlarni qayta ishlash va model qurish jarayonlari to'liq **Scikit-Learn Pipeline** orqali avtomatlashtirilgan.

## 📌 Kontekst va Ma'lumotlar tavsifi
Ma'lumotlar to'plamida professor Hofmann tomonidan tayyorlangan 20 ta toifali va sonli atributga ega 1000 ta mijoz yozuvi mavjud. Har bir mijoz atributlar to'plamiga ko'ra **Good (Yaxshi)** yoki **Bad (Yomon)** kredit riski sifatida tasniflanadi.

**Atributlar:**
- `Age` (Yoshi)
- `Sex` (Jinsi)
- `Job` (Ish turi: 0 - malakasiz norezident, 1 - malakasiz rezident, 2 - malakali, 3 - yuqori malakali)
- `Housing` (Uy-joy turi: shaxsiy, ijaradagi, tekin)
- `Saving accounts` & `Checking account` (Jamg'arma va joriy hisobvaraqlar holati)
- `Credit amount` (Kredit miqdori)
- `Duration` (Kredit muddati, oylarda)
- `Purpose` (Kredit maqsadi: mashina, ta'lim, biznes va h.k.)
- **Risk (Target)** - Yaxshi yoki Yomon risk.

## 🛠 Ishlatilgan Texnologiyalar
- **Python 3.x**
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-Learn (Pipeline, ColumnTransformer, GridSearchCV)
- **Advanced Models:** XGBoost Classifier, RandomForest Classifier
- **Model Explainability:** SHAP (SHapley Additive exPlanations)

## Loyiha Strukturasi va Algoritmlar
1. **EDA (Exploratory Data Analysis):** Ma'lumotlar taqsimoti va korrelyatsiyalar tahlil qilindi.
2. **Missing Values Imputation:** Bo'sh qiymatlar to'ldirildi va toifali o'zgaruvchilar OneHotEncoder orqali kodlandi.
3. **Pipeline Modeling:** Model va preprocessor ajratilgan holda Pipeline tizimiga yig'ildi.
4. **Hyperparameter Tuning:** GridSearchCV yordamida RandomForest va XGBoost modellari optimallashtirildi.
5. **Model Explainability:** SHAP kutubxonasi orqali model qarorlariga qaysi faktorlar eng ko'p ta'sir qilgani ko'rsatib berildi.

## 💻 Loyihani ishga tushirish

1. Repozitoriyani yuklab oling:
```bash
git clone [https://github.com/yourusername/german-credit-risk.git](https://github.com/yourusername/german-credit-risk.git)
cd -credit-risk

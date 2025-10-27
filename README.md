# 🗣️ Using Linguistic Diversity: Chinese Language Processing Analysis

A psycholinguistics study analyzing how Mandarin Chinese speakers process language in real-time using eye-tracking data.

---

## 📊 Project Overview

This project analyzes **65,434 eye-tracking observations** to understand how people comprehend Mandarin Chinese sentences when the meaning is ambiguous until the final word.

**Key Question:** Do listeners wait for the final word, or do they predict meaning earlier using context?

---

## 🎯 The Research Problem

In Mandarin Chinese, some sentences are identical until the last word:

- ❓ **Question**: woman-wear-is-**what** ("What is the woman wearing?")
- 💬 **Statement**: woman-wear-is-**shoes** ("The woman is wearing shoes")

These sentences sound exactly the same until you hear the final word. This lets researchers study how the brain processes ambiguous language.

---

## 📁 Dataset

- **Source**: Eye-tracking study of Mandarin comprehension
- **Size**: 65,434 observations
- **Participants**: 59 native Mandarin speakers
- **Items**: 24 linguistic stimuli
- **Duration**: ~5.5 seconds per trial
- **Measurements**: Where participants looked while listening to sentences

**Key Features:**
- `Target`: Proportion of time looking at the target object
- `Competitor`: Proportion looking at competitor object
- `Time`: Timestamp in seconds
- `Participant`: Individual subject ID
- `Item`: Stimulus ID

---

## 🔬 What We Did

### 1. **Exploratory Data Analysis**
- Analyzed gaze patterns over time
- Examined individual differences across participants
- Studied item-specific effects
- Investigated competition between target and competitor objects

### 2. **Time-Series Analysis**
- Tracked how attention changes from sentence start to end
- Identified when listeners begin predicting meaning
- Analyzed temporal dynamics of comprehension

### 3. **Statistical Modeling**
- Built machine learning models to predict gaze behavior
- Identified most important factors driving attention
- Achieved **~70% variance explained** (R² ≈ 0.70)

---

## 💡 Key Findings

### ✅ Main Discovery
**People don't wait for the final word!** They use context to predict meaning and shift attention to targets BEFORE hearing the disambiguating information.

### 📈 Specific Results

1. **Time is Critical**: Target fixations increase by **35%** from start to end of trial
2. **Early Prediction**: Listeners predict targets using context, not just linguistic form
3. **Individual Differences**: People use different but consistent processing strategies
4. **Competition Matters**: Attention alternates between target and competitors before settling
5. **Context > Form**: Task context allows comprehension even when language is ambiguous

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Statistics**: SciPy, Statsmodels
- **Machine Learning**: Scikit-learn, XGBoost, LightGBM

---

## 📂 Repository Structure
```
├── data/
│   └── Using Linguistic Diversity China.csv
├── notebooks/
│   └── analysis.ipynb                    # Main analysis notebook
├── visualizations/
│   └── figures/                          # Generated plots
├── README.md                             # This file
└── requirements.txt                      # Python dependencies
```

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn xgboost lightgbm
```

### Run the Analysis
1. Clone this repository
2. Open `notebooks/analysis.ipynb` in Jupyter
3. Run all cells to reproduce the analysis

---

## 📊 Sample Visualizations

The notebook includes:
- 📈 Temporal dynamics of gaze patterns
- 👥 Individual participant differences
- 📄 Item-specific effects
- 🔗 Feature correlations
- 🎯 Model predictions vs actual fixations
- 🌟 Feature importance rankings

---

## 🎓 What This Means

**For Language Science:**
- Comprehension is predictive, not just reactive
- Context matters as much as linguistic form
- Processing strategies vary across individuals

**For Cognitive Science:**
- Brain actively predicts upcoming information
- Real-time comprehension integrates multiple sources
- Eye movements reveal hidden cognitive processes

**For Practical Applications:**
- Better speech recognition systems (use context)
- Improved language teaching (teach prediction)
- Clinical assessment tools (detect processing issues)

---

## 📝 Citation

If you use this analysis, please cite:
```
[Original Study Citation - if available]
```

---

## 📧 Contact

Questions? Feel free to open an issue or reach out!

---

## 📜 License

This project is licensed under the MIT License - see LICENSE file for details.

---

## 🙏 Acknowledgments

- Original research team for collecting the eye-tracking data
- Kaggle community for dataset hosting and inspiration
- Open source Python data science community

---

**⭐ If you found this analysis useful, please star the repository!**

<div align="center">

# Abhishek Goyal
### **Machine Learning & NLP Engineer**
*msc math @ iit delhi · building ML systems that ship — from data to deployment*

[![Portfolio](https://img.shields.io/badge/Portfolio-goyashek.github.io-blue?style=flat-square)](https://goyashek.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-abhishek--goyal-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/abhishek-goyal-246b30211)
[![Twitter/X](https://img.shields.io/badge/Twitter-%40goyashek-1DA1F2?style=flat-square&logo=twitter)](https://x.com/goyashek)

</div>

---

### 🎯 Core Focus
* **Hybrid Architectures**: Bridging classical tree-based models (XGBoost/CatBoost) with deep metric learning (Siamese CNNs) and Transformer-based NLP (DistilBERT).
* **Robust Evaluation**: Designing leak-free splitting protocols (skeleton-aware) and auditing open datasets to identify data leaks.
* **Production Deployment**: Wrapping models in interactive Streamlit and Hugging Face spaces for live inference.

---

### 📂 Selected Projects

#### **Deep Metric Learning & Transformers**
* ✍️ **[Signature Forgery Verification](https://github.com/goyashek/Signature-forgery-verification)**
  * **Motive:** Build a writer-independent signature verifier that generalizes to unseen writers, while identifying and mitigating data leakage in standard ICDAR datasets.
  * **Tech:** Siamese CNN & fine-tuned EfficientNet-B0 + online batch-hard mining.
  * **Result:** Achieved **0.986 ROC-AUC** and mitigated a systemic dataset leak to establish a robust writer-independent evaluation protocol.
  * *[HF Space Demo](https://huggingface.co/spaces/goyashek/signature-forgery-verification)*
* 🛡️ **[Dark Pattern Detector](https://github.com/goyashek/dark-pattern-detector)**
  * **Motive:** Audit and detect CCPA-illegal manipulative UI patterns (dark patterns) on e-commerce platforms to protect consumers.
  * **Tech:** Fine-tuned DistilBERT vs. Optuna-tuned classical models (XGBoost/SVC).
  * **Result:** Achieved **0.797 macro-F1** under strict skeleton-aware, leak-free splits for 13 compliance categories.
  * *[Classical Demo](https://dark-patterns.streamlit.app/) · [Transformer Demo](https://huggingface.co/spaces/goyashek/distilbert-darkpattern)*

#### **Tabular Models & Predictors**
* 💰 **[Tech Salary Advisor](https://github.com/goyashek/Tech-Salary-Advisor)**
  * **Motive:** Quantify skill premiums and cost-of-living adjustments to help Indian tech workers negotiate salary transparency.
  * **Tech:** CatBoost regressor optimized with Optuna.
  * **Result:** Achieved **0.8753 R²** on 88K tech worker profiles, mapping compensation across roles and cities.
  * *[Streamlit Demo](https://tech-salary-advisor.streamlit.app/)*
* ✈️ **[Flight Delay Prediction](https://github.com/goyashek/Flight-Delay-Prediction)**
  * **Motive:** Predict flight delays using strictly pre-departure features to serve as a traveler warning system.
  * **Tech:** Benchmark of 6 estimators; deployed pre-departure XGBoost model.
  * **Result:** Achieved **0.773 ROC-AUC** for binary flight delay classification.
  * *[Streamlit Demo](https://flight-delay-xgb.streamlit.app/)*

#### **Interactive Dashboards**
* 📖 **[ML Cheat Sheet](https://github.com/goyashek/ml-cheat-sheet)**
  * **Motive:** Create a zero-dependency, rapid-lookup reference tool and decision wizard to help developers select optimal models and validation methods.
  * **Tech:** Vanilla JS, HSL Tailwind-like CSS variables (no external dependencies).
  * **Result:** Deployed an interactive dashboard covering 50+ ML techniques.
  * *[Live Site](https://goyashek.github.io/ml-cheat-sheet/)*
* 🔤 **[NLP Companion](https://github.com/goyashek/nlp-companion)**
  * **Motive:** Provide a quick-reference concept companion and pipeline integrity diagnostic quiz for NLP practitioners.
  * **Tech:** Vanilla JS, styled component cards.
  * **Result:** Deployed an interactive dashboard covering text preprocessing, word embeddings, and sequences.
  * *[Live Site](https://goyashek.github.io/nlp-companion/)*

---

### 🛠️ Skills & Ecosystem
```text
┌─────────────────┬────────────────────────────────────────────────────────┐
│ Machine Learning│ scikit-learn · Optuna · XGBoost · CatBoost             │
├─────────────────┼────────────────────────────────────────────────────────┤
│ Deep Learning   │ PyTorch · TensorFlow · Keras · Hugging Face            │
├─────────────────┼────────────────────────────────────────────────────────┤
│ NLP / Text      │ spaCy · NLTK · DistilBERT                              │
├─────────────────┼────────────────────────────────────────────────────────┤
│ Deploy & MLOps  │ Streamlit · Hugging Face Spaces · GitHub Pages · DVC   │
└─────────────────┴────────────────────────────────────────────────────────┘
```

---

<div align="center">
  <img src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=goyashek&theme=nord_dark" height="150" alt="GitHub stats" style="display: inline-block; margin-right: 10px;" />
  <img src="https://github-readme-streak-stats.herokuapp.com?user=goyashek&hide_border=true&ring=88c0d0&fire=88c0d0&currStreakLabel=88c0d0&sideLabels=eceff4&currStreakNum=eceff4&sideNums=eceff4&dates=d8dee9&background=2e3440" height="150" alt="GitHub streak" style="display: inline-block;" />
</div>

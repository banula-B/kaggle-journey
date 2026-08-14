# 🏆 52-Week Kaggle Beginner to Expert — Day-by-Day Roadmap

> A complete 364-day schedule. Each day has specific, actionable tasks. Follow this strictly for maximum progress.

---

## 📋 How to Use This Roadmap

- **Daily Time Commitment:** 1.5–3 hours on weekdays, 3–5 hours on weekends.
- **GitHub:** Commit something meaningful every single day.
- **Kaggle:** Log your progress in your Kaggle tracker.
- **Rest:** If you miss a day, do NOT skip. Resume the next day and adjust.

---

# 🗓️ PHASE 1 — Kaggle + Python Foundations (Days 1–28)

---

## Week 01 — Set Up Your Kaggle System

| Day | Task |
|-----|------|
| **Day 1 (Mon)** | Create your Kaggle account. Complete your profile (bio, photo, location). Explore the Kaggle homepage, competitions tab, datasets tab, and notebooks tab. |
| **Day 2 (Tue)** | Read the rules of 3 active competitions. Understand how leaderboards work (public vs private). Read Kaggle's "Getting Started" documentation. |
| **Day 3 (Wed)** | Explore 5 popular Kaggle datasets. Download one CSV dataset and open it locally. Understand the dataset page structure (description, files, kernels, discussion). |
| **Day 4 (Thu)** | Create a GitHub repository named `kaggle-journey`. Add a `README.md` with your goals. Set up the folder structure: `courses/`, `competitions/`, `notebooks/`, `projects/`. |
| **Day 5 (Fri)** | Create `KAGGLE_TRACKER.md` in your repo. Add a table for tracking courses, competitions, notebooks, and medals. **Commit:** `Initialize Kaggle tracker`. |
| **Day 6 (Sat)** | Join the **Titanic: Machine Learning from Disaster** competition. Read the competition overview, data description, and evaluation metric. Download the dataset. |
| **Day 7 (Sun)** | Write a `learning-roadmap.md` in your repo summarizing your 52-week plan. Review your GitHub repo structure. **Commit:** `Add learning roadmap and finalize setup`. |

**Week 1 GitHub Targets:** 5–7 meaningful commits.

---

## Week 02 — Kaggle Python Course

| Day | Task |
|-----|------|
| **Day 8 (Mon)** | Start the **Kaggle Python course** — Lesson 1 (Syntax, Variables, Numbers). Take notes in `courses/python/notes.md`. |
| **Day 9 (Tue)** | Kaggle Python — Lesson 2 (Functions, Help). Practice writing 10 custom functions. **Commit:** `Add Python functions notes and exercises`. |
| **Day 10 (Wed)** | Kaggle Python — Lesson 3 (Booleans, Conditionals). Build a small quiz program using conditionals. Save as `exercises.ipynb`. |
| **Day 11 (Thu)** | Kaggle Python — Lesson 4 (Lists). Practice list operations: slicing, appending, sorting. Solve 5 list manipulation problems. |
| **Day 12 (Fri)** | Kaggle Python — Lesson 5 (Loops, List Comprehensions). Rewrite 3 loop solutions using list comprehensions. **Commit:** `Add loops and list comprehension exercises`. |
| **Day 13 (Sat)** | Kaggle Python — Lesson 6 (Strings, Dictionaries). Build a word-frequency counter using dictionaries. |
| **Day 14 (Sun)** | Kaggle Python — Final exercises + course completion. Review all notes. **Commit:** `Complete Kaggle Python course`. Mark as done in `KAGGLE_TRACKER.md`. |

**Week 2 GitHub Targets:** 5–7 commits.

---

## Week 03 — NumPy Mastery

| Day | Task |
|-----|------|
| **Day 15 (Mon)** | Start NumPy: arrays, `np.array()`, `shape`, `dtype`. Create arrays of different dimensions. Take notes in `courses/numpy/notes.md`. |
| **Day 16 (Tue)** | NumPy indexing and slicing (1D, 2D, 3D arrays). Practice fancy indexing and boolean masking. |
| **Day 17 (Wed)** | NumPy broadcasting rules. Solve 5 broadcasting exercises. Understand when broadcasting works and when it fails. |
| **Day 18 (Thu)** | NumPy mathematical operations: `np.sum()`, `np.mean()`, `np.std()`, `np.dot()`, matrix multiplication. **Commit:** `Add NumPy math operations exercises`. |
| **Day 19 (Fri)** | NumPy vectorization: rewrite 3 loop-based operations using vectorized NumPy. Compare speed using `%timeit`. |
| **Day 20 (Sat)** | **Mini-Project:** Load a Kaggle dataset into NumPy. Perform data cleaning (handle NaNs, filter rows) using only NumPy. Save as `notebooks/numpy-data-analysis.ipynb`. |
| **Day 21 (Sun)** | Review your NumPy notebook. Add markdown explanations. Polish and publish on Kaggle as a notebook. **Commit:** `Publish NumPy data analysis mini-project`. |

**Week 3 GitHub Targets:** 5–7 commits.

---

## Week 04 — Pandas Mastery

| Day | Task |
|-----|------|
| **Day 22 (Mon)** | Start the **Kaggle Pandas course** — Lesson 1 (Creating, Reading, Writing data). Learn `pd.DataFrame`, `pd.Series`, `read_csv()`. |
| **Day 23 (Tue)** | Kaggle Pandas — Lesson 2 (Indexing, Selecting, Assigning). Practice `.loc`, `.iloc`, column selection. Take notes in `courses/pandas/notes.md`. |
| **Day 24 (Wed)** | Kaggle Pandas — Lesson 3 (Summary Functions, Maps). Use `describe()`, `value_counts()`, `map()`, `apply()`. |
| **Day 25 (Thu)** | Kaggle Pandas — Lesson 4 (Grouping, Sorting). Master `groupby()`, `sort_values()`, aggregation with `.agg()`. **Commit:** `Add Pandas grouping and sorting exercises`. |
| **Day 26 (Fri)** | Kaggle Pandas — Lesson 5 (Data Types, Missing Values). Handle `NaN` with `fillna()`, `dropna()`. Convert data types using `astype()`. |
| **Day 27 (Sat)** | Kaggle Pandas — Lesson 6 (Renaming, Combining). Practice `merge()`, `concat()`, `join()`. Complete the Pandas course. **Commit:** `Complete Kaggle Pandas course`. |
| **Day 28 (Sun)** | **Project:** Build a complete CSV Data Analysis project using Pandas. Load a real dataset, clean it, and generate 5 insights with visualizations. Save in `projects/csv-analysis/`. **Commit:** `Add CSV data analysis project`. |

**Week 4 GitHub Targets:** 5–7 commits.

---

# 🗓️ PHASE 2 — Data Analysis + Visualization (Days 29–56)

---

## Week 05 — Data Cleaning

| Day | Task |
|-----|------|
| **Day 29 (Mon)** | Learn missing value patterns: MCAR, MAR, MNAR. Identify missing values in a dataset. Document strategies: deletion, imputation (mean, median, mode). |
| **Day 30 (Tue)** | Practice handling duplicates with `drop_duplicates()`. Detect and remove duplicate rows and columns. **Commit:** `Add data cleaning — duplicates handling`. |
| **Day 31 (Wed)** | Data type conversion: strings to datetime, categorical encoding, numeric coercion. Fix type mismatches in a real dataset. |
| **Day 32 (Thu)** | Outlier detection: Z-score, IQR method, visual detection (boxplots). Create a notebook detecting outliers in 2 datasets. |
| **Day 33 (Fri)** | Encoding categorical variables: One-Hot Encoding, Label Encoding, Ordinal Encoding. Practice on a dataset with mixed types. **Commit:** `Add encoding and outlier detection notebook`. |
| **Day 34 (Sat)** | **Project:** Choose a messy real-world dataset from Kaggle Datasets. Clean it completely: handle missing values, duplicates, outliers, encoding, type fixes. Save in `projects/data-cleaning/`. |
| **Day 35 (Sun)** | Document your cleaning process in a `README.md`. Explain every decision. Publish the cleaned dataset/notebook on Kaggle. **Commit:** `Complete data cleaning project with documentation`. |

**Week 5 GitHub Targets:** 5–7 commits.

---

## Week 06 — Data Visualization

| Day | Task |
|-----|------|
| **Day 36 (Mon)** | Start the **Kaggle Data Visualization course** — Lesson 1 (Hello Seaborn). Learn `sns.lineplot()`, `sns.scatterplot()`. |
| **Day 37 (Tue)** | Data Visualization — Lesson 2 (Bar Charts, Heatmaps). Practice `sns.barplot()`, `sns.heatmap()`, correlation heatmaps. |
| **Day 38 (Wed)** | Data Visualization — Lesson 3 (Distributions). Master `sns.histplot()`, `sns.kdeplot()`, `sns.boxplot()`, `sns.violinplot()`. |
| **Day 39 (Thu)** | Matplotlib fundamentals: `plt.figure()`, `plt.plot()`, subplots, styling (titles, labels, legends). Build 5 custom plots from scratch. **Commit:** `Add Matplotlib fundamentals exercises`. |
| **Day 40 (Fri)** | Advanced Seaborn: `sns.pairplot()`, `sns.jointplot()`, `sns.catplot()`, faceting with `FacetGrid`. |
| **Day 41 (Sat)** | Complete the Kaggle Data Visualization course. Combine Matplotlib + Seaborn in one polished notebook. **Commit:** `Complete Data Visualization course`. |
| **Day 42 (Sun)** | **Project:** Create `notebooks/exploratory-data-analysis.ipynb`. Load a dataset, perform full EDA with 10+ visualizations, and write insights in markdown. **Commit:** `Add complete EDA notebook`. |

**Week 6 GitHub Targets:** 5–7 commits.

---

## Week 07 — EDA Project

| Day | Task |
|-----|------|
| **Day 43 (Mon)** | Select a dataset for your first polished EDA project. Write a project plan: questions to answer, expected visualizations, target insights. |
| **Day 44 (Tue)** | Load and inspect the dataset. Document shape, columns, dtypes, missing values. **Commit:** `Add EDA project — data loading and inspection`. |
| **Day 45 (Wed)** | Data cleaning for EDA: handle missing values, outliers, and inconsistencies. |
| **Day 46 (Thu)** | Univariate analysis: distributions of all key variables. Generate 5+ distribution plots. |
| **Day 47 (Fri)** | Bivariate and multivariate analysis: correlations, relationships, group comparisons. Generate 5+ relationship plots. **Commit:** `Add EDA project — bivariate analysis`. |
| **Day 48 (Sat)** | Synthesize insights. Write a compelling narrative in markdown. Add a summary section with actionable findings. Polish the notebook. |
| **Day 49 (Sun)** | Publish the EDA notebook on Kaggle. Share on social media or Kaggle discussions. Add a `README.md` in `projects/eda-project/`. **Commit:** `Publish polished EDA project`. |

**Week 7 GitHub Targets:** 5–7 commits.

---

## Week 08 — First Competition: Titanic

| Day | Task |
|-----|------|
| **Day 50 (Mon)** | Re-read the Titanic competition page. Understand the problem (binary classification), features, and submission format. Load `train.csv` and `test.csv`. |
| **Day 51 (Tue)** | Perform EDA on the Titanic dataset. Analyze survival rates by sex, age, class, fare. Create visualizations. **Commit:** `Add Titanic EDA notebook`. |
| **Day 52 (Wed)** | Build your first baseline model: simple heuristic (e.g., "all females survive"). Create a submission CSV. Submit to Kaggle. Record your score. |
| **Day 53 (Thu)** | Learn train/test split. Build a Decision Tree model using scikit-learn. Evaluate with accuracy. **Commit:** `Add Titanic decision tree baseline`. |
| **Day 54 (Fri)** | Try a Random Forest model. Compare with Decision Tree. Experiment with `n_estimators`. Document scores. |
| **Day 55 (Sat)** | Improve features: handle missing Age (imputation), encode Sex, create FamilySize. Retrain and submit. **Commit:** `Add Titanic feature engineering v1`. |
| **Day 56 (Sun)** | Final Titanic submission. Document your best approach in `competitions/titanic/README.md`. Record final score and rank in `KAGGLE_TRACKER.md`. **Commit:** `Complete Titanic competition — final documentation`. |

**Week 8 GitHub Targets:** 5–7 commits.

---

# 🗓️ PHASE 3 — Machine Learning Foundations (Days 57–84)

---

## Week 09 — Intro to Machine Learning

| Day | Task |
|-----|------|
| **Day 57 (Mon)** | Start the **Kaggle Intro to Machine Learning** course. Lesson 1: How Models Work. Understand decision trees intuitively. |
| **Day 58 (Tue)** | Lesson 2: Basic Data Exploration. Practice `describe()`, selecting features and target. |
| **Day 59 (Wed)** | Lesson 3: Your First Machine Learning Model. Build a Decision Tree in scikit-learn. Understand `fit()` and `predict()`. |
| **Day 60 (Thu)** | Lesson 4: Model Validation. Learn train/test split, MAE (Mean Absolute Error). **Commit:** `Add ML model validation exercises`. |
| **Day 61 (Fri)** | Lesson 5: Underfitting and Overfitting. Experiment with `max_leaf_nodes`. Plot validation curve. |
| **Day 62 (Sat)** | Lesson 6: Random Forests. Build a Random Forest, compare with Decision Tree. Complete the course. **Commit:** `Complete Intro to ML course`. |
| **Day 63 (Sun)** | Review all ML notes. Build a mini-project predicting a target from a Kaggle dataset using Random Forest. Save in `courses/intro-to-ml/`. **Commit:** `Add Intro to ML mini-project`. |

**Week 9 GitHub Targets:** 5–7 commits.

---

## Week 10 — Validation Strategies

| Day | Task |
|-----|------|
| **Day 64 (Mon)** | Deep dive into train/validation/test splits. Why 3 sets? Understand the purpose of each. |
| **Day 65 (Tue)** | Implement K-Fold Cross-Validation manually (5-fold). Compare CV scores with single split scores. **Commit:** `Add K-Fold CV implementation`. |
| **Day 66 (Wed)** | Learn about overfitting: symptoms, causes, detection. Build an overfit model intentionally and demonstrate it. |
| **Day 67 (Thu)** | Learn about underfitting. Compare underfit, good-fit, and overfit models on the same dataset. Plot learning curves. |
| **Day 68 (Fri)** | Study data leakage: target leakage, train-test contamination. Read 2 Kaggle discussion posts about leakage. **Commit:** `Add data leakage study notes`. |
| **Day 69 (Sat)** | **Titanic V2:** Rebuild your Titanic solution with proper validation. Use 5-Fold CV. Compare your new reliable score with your old single-split score. |
| **Day 70 (Sun)** | **Titanic V3:** Experiment with different validation strategies. Document which validation strategy gives the most stable estimates. **Commit:** `Add Titanic validation experiments v2 and v3`. |

**Week 10 GitHub Targets:** 5–7 commits.

---

## Week 11 — Feature Engineering Basics

| Day | Task |
|-----|------|
| **Day 71 (Mon)** | Learn numerical feature transformations: log transform, square root, binning. Apply to a dataset. |
| **Day 72 (Tue)** | Categorical feature engineering: One-Hot Encoding, Label Encoding, Frequency Encoding. Practice on 2 datasets. **Commit:** `Add categorical encoding experiments`. |
| **Day 73 (Wed)** | Feature creation: derive new features from existing ones (ratios, interactions, date parts). Build 5 new features for Titanic. |
| **Day 74 (Thu)** | Feature selection: correlation analysis, mutual information, univariate statistical tests. Select top features for a model. |
| **Day 75 (Fri)** | Build an experiment tracker table. Create `experiments.md` with columns: Version, Features Added, CV Score, LB Score. **Commit:** `Initialize experiment tracker`. |
| **Day 76 (Sat)** | **Titanic V4:** Add engineered features (Title from Name, FamilySize, IsAlone). Track in experiment tracker. Submit and record score. |
| **Day 77 (Sun)** | **Titanic V5:** Try a different feature set. Compare V4 vs V5. Document what worked and why. **Commit:** `Add Titanic feature engineering v4 and v5`. |

**Week 11 GitHub Targets:** 5–7 commits.

---

## Week 12 — First Competition Review

| Day | Task |
|-----|------|
| **Day 78 (Mon)** | Review your entire Titanic journey. Gather all notebooks, submissions, and scores. |
| **Day 79 (Tue)** | Write a retrospective: What worked? What failed? Best model? Best features? Validation strategy used? Save as `competitions/titanic/RETROSPECTIVE.md`. |
| **Day 80 (Wed)** | Clean up your Titanic GitHub folder. Ensure all notebooks run end-to-end. Add a comprehensive `README.md`. **Commit:** `Polish Titanic competition documentation`. |
| **Day 81 (Thu)** | Read top 5 Titanic notebooks on Kaggle. Note techniques you missed. Document learnings in `competitions/titanic/LEARNINGS.md`. |
| **Day 82 (Fri)** | Implement 2 new techniques from top notebooks into a `titanic-bonus-experiments.ipynb`. **Commit:** `Add Titanic bonus experiments from community`. |
| **Day 83 (Sat)** | Finalize your Titanic project. Ensure reproducibility: add data loading, clear comments, markdown explanations. |
| **Day 84 (Sun)** | Update `KAGGLE_TRACKER.md` with final Titanic stats. Celebrate completing your first competition! Plan next steps. **Commit:** `Finalize Phase 3 — ML Foundations complete`. |

**Week 12 GitHub Targets:** 5–7 commits.

---

# 🗓️ PHASE 4 — Intermediate Tabular ML (Days 85–112)

---

## Week 13 — Intermediate Machine Learning

| Day | Task |
|-----|------|
| **Day 85 (Mon)** | Start the **Kaggle Intermediate Machine Learning** course. Lesson 1: Introduction. Review prerequisites. |
| **Day 86 (Tue)** | Lesson 2: Missing Values. Learn 3 approaches: drop columns, imputation, extension. Practice on a dataset. |
| **Day 87 (Wed)** | Lesson 3: Categorical Variables. Handle cardinal, ordinal, and nominal variables. **Commit:** `Add categorical variables handling exercises`. |
| **Day 88 (Thu)** | Lesson 4: Pipelines. Build your first scikit-learn `Pipeline` with `ColumnTransformer`. |
| **Day 89 (Fri)** | Lesson 5: Cross-Validation. Implement CV with pipelines. **Commit:** `Add pipeline + CV exercises`. |
| **Day 90 (Sat)** | Lesson 6: XGBoost. Install XGBoost. Train your first XGBoost model. Compare with Random Forest. |
| **Day 91 (Sun)** | Complete the Intermediate ML course. Review all lessons. Save notes in `courses/intermediate-ml/`. **Commit:** `Complete Intermediate ML course`. |

**Week 13 GitHub Targets:** 5–7 commits.

---

## Week 14 — Scikit-learn Pipelines

| Day | Task |
|-----|------|
| **Day 92 (Mon)** | Deep dive into `Pipeline`: why use it? Build a simple pipeline (imputer → scaler → model). |
| **Day 93 (Tue)** | Master `ColumnTransformer`: apply different transformations to numerical and categorical columns. **Commit:** `Add ColumnTransformer deep dive`. |
| **Day 94 (Wed)** | Build a complete preprocessing pipeline: missing value imputation, encoding, scaling, feature selection. |
| **Day 95 (Thu)** | Add custom transformers to your pipeline. Build a `FunctionTransformer` for log transforms. |
| **Day 96 (Fri)** | Pipeline + Cross-Validation integration. Run CV on your full pipeline. **Commit:** `Add full pipeline with CV integration`. |
| **Day 97 (Sat)** | **Project:** Refactor your Titanic solution into a clean, reproducible pipeline. One cell for pipeline definition, one for training, one for prediction. |
| **Day 98 (Sun)** | Document your pipeline project. Add a diagram showing the flow. Save in `projects/reproducible-pipeline/`. **Commit:** `Add reproducible ML pipeline project`. |

**Week 14 GitHub Targets:** 5–7 commits.

---

## Week 15 — House Prices Competition — Baseline

| Day | Task |
|-----|------|
| **Day 99 (Mon)** | Join the **House Prices: Advanced Regression Techniques** competition. Read all documentation. Understand RMSE and log-transformed RMSE. |
| **Day 100 (Tue)** | Load and explore the House Prices dataset. EDA: target distribution, missing values, feature types. **Commit:** `Add House Prices EDA`. |
| **Day 101 (Wed)** | Build a baseline model: simple linear regression with minimal preprocessing. Submit and record score. |
| **Day 102 (Thu)** | Learn regression metrics: RMSE, MAE, R². Understand why House Prices uses log-RMSE. **Commit:** `Add regression metrics study`. |
| **Day 103 (Fri)** | Handle missing values in House Prices. Compare dropping vs imputation strategies. |
| **Day 104 (Sat)** | Encode categorical variables in House Prices. Try One-Hot and Ordinal encoding. Track CV scores. **Commit:** `Add House Prices encoding experiments`. |
| **Day 105 (Sun)** | Submit your improved baseline. Document the approach in `competitions/house-prices/README.md`. **Commit:** `Add House Prices baseline submission`. |

**Week 15 GitHub Targets:** 5–7 commits.

---

## Week 16 — House Prices Competition — Experiments

| Day | Task |
|-----|------|
| **Day 106 (Mon)** | Experiment 1: Random Forest baseline for House Prices. Tune `n_estimators` and `max_depth`. |
| **Day 107 (Tue)** | Experiment 2: Gradient Boosting (sklearn). Compare with Random Forest. **Commit:** `Add House Prices Random Forest and Gradient Boosting`. |
| **Day 108 (Wed)** | Experiment 3: XGBoost for regression. Tune `learning_rate`, `max_depth`, `n_estimators`. |
| **Day 109 (Thu)** | Experiment 4: Feature engineering for House Prices. Create TotalSF, HouseAge, RemodAge. **Commit:** `Add House Prices feature engineering`. |
| **Day 110 (Fri)** | Experiment 5: Log transform the target. Compare CV scores with and without log transform. |
| **Day 111 (Sat)** | Run a final ensemble of your best models. Submit the ensemble. Document all experiments in a table. |
| **Day 112 (Sun)** | Finalize House Prices. Write retrospective. Update `KAGGLE_TRACKER.md`. **Commit:** `Complete House Prices competition`. |

**Week 16 GitHub Targets:** 5–7 commits.

---

# 🗓️ PHASE 5 — Feature Engineering + Model Tuning (Days 113–140)

---

## Week 17 — Feature Engineering Course

| Day | Task |
|-----|------|
| **Day 113 (Mon)** | Start the **Kaggle Feature Engineering** course. Lesson 1: What is Feature Engineering? |
| **Day 114 (Tue)** | Lesson 2: Mutual Information. Calculate MI scores for a dataset. Select top features. **Commit:** `Add mutual information exercises`. |
| **Day 115 (Wed)** | Lesson 3: Creating Features. Build ratio features, interaction features, and group transforms. |
| **Day 116 (Thu)** | Lesson 4: Clustering with K-Means. Use K-Means as a feature engineering technique. |
| **Day 117 (Fri)** | Lesson 5: Principal Component Analysis. Use PCA for feature extraction. **Commit:** `Add K-Means and PCA feature engineering`. |
| **Day 118 (Sat)** | Lesson 6: Target Encoding. Learn when and how to use target encoding safely. Complete the course. |
| **Day 119 (Sun)** | Review all feature engineering techniques. Build a cheat sheet. Save in `courses/feature-engineering/cheat-sheet.md`. **Commit:** `Complete Feature Engineering course + cheat sheet`. |

**Week 17 GitHub Targets:** 5–7 commits.

---

## Week 18 — Advanced Validation

| Day | Task |
|-----|------|
| **Day 120 (Mon)** | Deep dive into K-Fold CV: when to use it, pitfalls, implementation. |
| **Day 121 (Tue)** | Stratified K-Fold: why and when. Implement StratifiedKFold for a classification problem. **Commit:** `Add Stratified K-Fold implementation`. |
| **Day 122 (Wed)** | Group K-Fold: for grouped data. Understand when standard CV fails. |
| **Day 123 (Thu)** | Time-Series validation: purged cross-validation, walk-forward validation. Read about time-aware splits. **Commit:** `Add time-series validation study`. |
| **Day 124 (Fri)** | Build a validation strategy decision tree: "Which CV should I use?" Document it. |
| **Day 125 (Sat)** | **Practice:** Apply 3 different CV strategies to the same dataset. Compare score stability. |
| **Day 126 (Sun)** | Write a comprehensive validation guide. Save in `notes/validation-guide.md`. **Commit:** `Add comprehensive validation strategy guide`. |

**Week 18 GitHub Targets:** 5–7 commits.

---

## Week 19 — Boosting Algorithms

| Day | Task |
|-----|------|
| **Day 127 (Mon)** | XGBoost deep dive: parameters, objective functions, boosting rounds. Read XGBoost documentation. |
| **Day 128 (Tue)** | LightGBM: install and train your first model. Compare speed and accuracy with XGBoost. **Commit:** `Add LightGBM introduction and comparison`. |
| **Day 129 (Wed)** | CatBoost: install and train. Understand categorical feature handling. Compare with XGBoost and LightGBM. |
| **Day 130 (Thu)** | Compare all 3 on the same dataset. Build a comparison table: speed, CV score, memory usage. **Commit:** `Add XGBoost vs LightGBM vs CatBoost benchmark`. |
| **Day 131 (Fri)** | Study when to use each: small data, large data, many categorical features, GPU availability. |
| **Day 132 (Sat)** | Tune an XGBoost model: `max_depth`, `learning_rate`, `subsample`, `colsample_bytree`. |
| **Day 133 (Sun)** | Tune a LightGBM model. Document best practices for each library. **Commit:** `Add boosting algorithms tuning guide`. |

**Week 19 GitHub Targets:** 5–7 commits.

---

## Week 20 — Hyperparameter Optimization

| Day | Task |
|-----|------|
| **Day 134 (Mon)** | Grid Search: implement `GridSearchCV`. Understand the curse of dimensionality in search space. |
| **Day 135 (Tue)** | Random Search: implement `RandomizedSearchCV`. Compare efficiency with Grid Search. **Commit:** `Add Grid Search vs Random Search comparison`. |
| **Day 136 (Wed)** | Install and learn Optuna. Build your first Optuna study. Understand trials, objectives, and pruners. |
| **Day 137 (Thu)** | Optuna advanced: multi-objective optimization, visualization, distributed optimization. |
| **Day 138 (Fri)** | Apply Optuna to XGBoost on a real dataset. Find optimal parameters. **Commit:** `Add Optuna hyperparameter tuning project`. |
| **Day 139 (Sat)** | **Project:** Build a reusable hyperparameter tuning script. Support Grid, Random, and Optuna. Save in `projects/hyperparameter-tuning/`. |
| **Day 140 (Sun)** | Document when to use each tuning method. Write best practices. **Commit:** `Add HPO best practices guide`. |

**Week 20 GitHub Targets:** 5–7 commits.

---

# 🗓️ PHASE 6 — Advanced Tabular ML (Days 141–168)

---

## Week 21 — New Tabular Competition

| Day | Task |
|-----|------|
| **Day 141 (Mon)** | Browse active Kaggle competitions. Choose a current Playground or Featured tabular competition. Read all rules and data descriptions. |
| **Day 142 (Tue)** | Download data. Perform initial EDA. Document dataset size, feature types, target distribution. **Commit:** `Add [Competition Name] EDA`. |
| **Day 143 (Wed)** | Build your own baseline from scratch. No copying public notebooks yet. Use a simple model (Logistic Regression / Linear Regression). |
| **Day 144 (Thu)** | Establish a validation strategy. Justify your choice based on data characteristics. **Commit:** `Add [Competition Name] baseline and validation`. |
| **Day 145 (Fri)** | Review 3 public notebooks for this competition. Note techniques, not code. Document insights. |
| **Day 146 (Sat)** | Implement 2 new ideas from public notebooks. Track experiments. |
| **Day 147 (Sun)** | Submit your first real attempt. Record CV and LB scores. **Commit:** `Add [Competition Name] first submission`. |

**Week 21 GitHub Targets:** 5–7 commits.

---

## Week 22 — Error Analysis

| Day | Task |
|-----|------|
| **Day 148 (Mon)** | Study your model's wrong predictions. Which rows did it get wrong? Any patterns? |
| **Day 149 (Tue)** | Feature importance analysis: plot feature importance from your tree-based model. **Commit:** `Add feature importance analysis`. |
| **Day 150 (Wed)** | Residual analysis (regression) or confusion matrix deep dive (classification). Identify systematic errors. |
| **Day 151 (Thu)** | Class imbalance check. If imbalanced, study precision/recall per class. **Commit:** `Add error analysis notebook`. |
| **Day 152 (Fri)** | SHAP values introduction. Install `shap`. Explain one prediction using SHAP. |
| **Day 153 (Sat)** | SHAP global analysis: summary plot, dependence plot. Understand model behavior globally. |
| **Day 154 (Sun)** | Document all error analysis findings. Create an action plan for improvement. **Commit:** `Add SHAP analysis and error action plan`. |

**Week 22 GitHub Targets:** 5–7 commits.

---

## Week 23 — Ensembling

| Day | Task |
|-----|------|
| **Day 155 (Mon)** | Learn Voting Ensemble: hard voting vs soft voting. Implement with scikit-learn `VotingClassifier`. |
| **Day 156 (Tue)** | Averaging ensemble for regression. Combine predictions from multiple models with simple average. **Commit:** `Add voting and averaging ensemble experiments`. |
| **Day 157 (Wed)** | Weighted averaging: assign weights based on CV performance. Compare with simple average. |
| **Day 158 (Thu)** | Blending: hold out a validation set for blending. Train meta-learner. |
| **Day 159 (Fri)** | Stacking: implement `StackingClassifier` / `StackingRegressor`. Understand out-of-fold predictions. **Commit:** `Add blending and stacking experiments`. |
| **Day 160 (Sat)** | Build your first full ensemble for your active competition. Combine 3+ diverse models. |
| **Day 161 (Sun)** | Submit ensemble. Compare with best single model. Document results. **Commit:** `Add first competition ensemble submission`. |

**Week 23 GitHub Targets:** 5–7 commits.

---

## Week 24 — Competition Sprint

| Day | Task |
|-----|------|
| **Day 162 (Mon)** | Review all experiments so far. Identify the top 3 ideas with highest ROI. |
| **Day 163 (Tue)** | Implement Idea 1: advanced feature engineering or new model. Track CV change. **Commit:** `Add competition sprint — idea 1`. |
| **Day 164 (Wed)** | Implement Idea 2: different ensemble strategy or hyperparameter tweak. |
| **Day 165 (Thu)** | Implement Idea 3: data augmentation or leakage fix. **Commit:** `Add competition sprint — ideas 2 and 3`. |
| **Day 166 (Fri)** | Final model selection. Choose your best single model and best ensemble. |
| **Day 167 (Sat)** | Final submission. Double-check submission format. Submit your strongest solution. |
| **Day 168 (Sun)** | Complete documentation: `README.md`, experiment table, final retrospective. Update `KAGGLE_TRACKER.md`. **Commit:** `Complete [Competition Name] — final documentation`. |

**Week 24 GitHub Targets:** 5–7 commits.

---

# 🗓️ PHASE 7 — Deep Learning (Days 169–196)

---

## Week 25 — Deep Learning Foundations

| Day | Task |
|-----|------|
| **Day 169 (Mon)** | Start the **Kaggle Intro to Deep Learning** course. Lesson 1: A Single Neuron. Understand linear units. |
| **Day 170 (Tue)** | Lesson 2: Deep Neural Networks. Understand hidden layers, activation functions (ReLU). |
| **Day 171 (Wed)** | Lesson 3: Stochastic Gradient Descent. Understand loss functions, optimizer, learning rate. **Commit:** `Add deep learning fundamentals notes`. |
| **Day 172 (Thu)** | Lesson 4: Overfitting and Underfitting. Learn dropout, early stopping, batch normalization. |
| **Day 173 (Fri)** | Lesson 5: Loss functions for regression and classification. Understand MSE, MAE, Binary Crossentropy, Categorical Crossentropy. **Commit:** `Add loss functions study`. |
| **Day 174 (Sat)** | Build your first neural network with Keras: a simple regression model on tabular data. |
| **Day 175 (Sun)** | Complete the Intro to Deep Learning course. Review all concepts. **Commit:** `Complete Intro to Deep Learning course`. |

**Week 25 GitHub Targets:** 5–7 commits.

---

## Week 26 — TensorFlow / PyTorch

| Day | Task |
|-----|------|
| **Day 176 (Mon)** | Choose your framework: TensorFlow/Keras OR PyTorch. Install and set up GPU support. Verify GPU is detected. |
| **Day 177 (Tue)** | Learn Tensors: creation, operations, indexing, reshaping. Practice with 10 tensor exercises. **Commit:** `Add tensor fundamentals exercises`. |
| **Day 178 (Wed)** | Datasets and DataLoaders: load data efficiently, batching, shuffling, preprocessing pipelines. |
| **Day 179 (Thu)** | Build a training loop from scratch: forward pass, loss calculation, backward pass, optimizer step. **Commit:** `Add custom training loop implementation`. |
| **Day 180 (Fri)** | Validation loops: evaluate on validation set, track metrics, save best model. |
| **Day 181 (Sat)** | GPU usage best practices: mixed precision, data transfer optimization. Train a model on GPU. |
| **Day 182 (Sun)** | **Project:** Build a complete training script: data loading, model definition, training, validation, checkpointing. Save in `deep-learning/fundamentals/`. **Commit:** `Add complete DL training pipeline`. |

**Week 26 GitHub Targets:** 5–7 commits.

---

## Week 27 — Neural Network Competition

| Day | Task |
|-----|------|
| **Day 183 (Mon)** | Find a beginner-friendly deep learning competition (e.g., Digit Recognizer or a Playground competition). Join it. |
| **Day 184 (Tue)** | EDA on the competition data. Understand image/tabular structure for DL. **Commit:** `Add DL competition EDA`. |
| **Day 185 (Wed)** | Build a simple neural network baseline. Train for a few epochs. Establish a validation split. |
| **Day 186 (Thu)** | Add regularization: Dropout, L2 regularization. Compare with unregularized model. **Commit:** `Add regularization experiments`. |
| **Day 187 (Fri)** | Add Batch Normalization. Compare training speed and stability. |
| **Day 188 (Sat)** | Experiment with learning rate scheduling. Try ReduceLROnPlateau or Cosine Annealing. |
| **Day 189 (Sun)** | Submit your best neural network. Document architecture and results. **Commit:** `Add DL competition submission`. |

**Week 27 GitHub Targets:** 5–7 commits.

---

## Week 28 — Deep Learning Project

| Day | Task |
|-----|------|
| **Day 190 (Mon)** | Plan an Image Classification project. Choose a dataset (e.g., CIFAR-10, Cats vs Dogs, or a Kaggle dataset). |
| **Day 191 (Tue)** | Load and preprocess image data. Resize, normalize, augment (flip, rotate). **Commit:** `Add image preprocessing pipeline`. |
| **Day 192 (Wed)** | Build a CNN from scratch: Conv2D, MaxPooling, Flatten, Dense layers. |
| **Day 193 (Thu)** | Train the CNN. Track training curves (loss, accuracy). Identify overfitting. **Commit:** `Add CNN from scratch training`. |
| **Day 194 (Fri)** | Improve the CNN: add more layers, regularization, data augmentation. Retrain. |
| **Day 195 (Sat)** | Evaluate the model. Generate classification report, confusion matrix. Visualize predictions. |
| **Day 196 (Sun)** | Polish and publish the project. Add `README.md`, requirements, and clear documentation. **Commit:** `Publish image classification DL project`. |

**Week 28 GitHub Targets:** 5–7 commits.

---

# 🗓️ PHASE 8 — Computer Vision (Days 197–224)

---

## Week 29 — Computer Vision Foundations

| Day | Task |
|-----|------|
| **Day 197 (Mon)** | Learn how images are represented: pixels, channels (RGB), tensors. Load and display images with matplotlib/OpenCV. |
| **Day 198 (Tue)** | CNN architecture deep dive: convolution, filters, feature maps, receptive field. Visualize filters and feature maps. **Commit:** `Add CNN visualization notebook`. |
| **Day 199 (Wed)** | Pooling layers: MaxPooling, AveragePooling, GlobalAveragePooling. Understand dimensionality reduction. |
| **Day 200 (Thu)** | Data Augmentation: rotation, scaling, flipping, color jittering. Implement with `ImageDataGenerator` or `torchvision.transforms`. **Commit:** `Add data augmentation experiments`. |
| **Day 201 (Fri)** | Popular CNN architectures: LeNet, AlexNet, VGG. Understand the evolution. |
| **Day 202 (Sat)** | Build a VGG-style network. Train on your chosen dataset. |
| **Day 203 (Sun)** | Document CNN fundamentals. Create a visual guide. **Commit:** `Add computer vision fundamentals guide`. |

**Week 29 GitHub Targets:** 5–7 commits.

---

## Week 30 — Transfer Learning

| Day | Task |
|-----|------|
| **Day 204 (Mon)** | Learn transfer learning concepts: pre-trained weights, feature extraction, fine-tuning. |
| **Day 205 (Tue)** | ResNet: understand residual connections. Load a pre-trained ResNet model. **Commit:** `Add ResNet transfer learning setup`. |
| **Day 206 (Wed)** | EfficientNet: understand compound scaling. Load pre-trained EfficientNet. Compare model sizes. |
| **Day 207 (Thu)** | Feature extraction: freeze backbone, train only classifier head. Compare with training from scratch. **Commit:** `Add feature extraction vs from-scratch comparison`. |
| **Day 208 (Fri)** | Fine-tuning: unfreeze layers, use differential learning rates. Train with fine-tuning. |
| **Day 209 (Sat)** | Build a transfer learning image classifier on a real dataset. Use your best pre-trained model. |
| **Day 210 (Sun)** | Evaluate and document. Save the best model weights. **Commit:** `Add transfer learning image classifier project`. |

**Week 30 GitHub Targets:** 5–7 commits.

---

## Week 31 — CV Competition

| Day | Task |
|-----|------|
| **Day 211 (Mon)** | Join an active computer vision competition. Read data description and evaluation metric carefully. |
| **Day 212 (Tue)** | EDA: visualize sample images, class distributions, image sizes. **Commit:** `Add CV competition EDA`. |
| **Day 213 (Wed)** | Build a baseline CNN from scratch. Train and validate. Record baseline score. |
| **Day 214 (Thu)** | Apply transfer learning: use ResNet/EfficientNet pre-trained on ImageNet. **Commit:** `Add CV competition transfer learning baseline`. |
| **Day 215 (Fri)** | Add data augmentation pipeline. Compare with no augmentation. |
| **Day 216 (Sat)** | Experiment with ensemble of CNNs: average predictions from 2–3 architectures. |
| **Day 217 (Sun)** | Submit your best CV model. Document architecture, augmentation, and results. **Commit:** `Add CV competition submission`. |

**Week 31 GitHub Targets:** 5–7 commits.

---

## Week 32 — CV Competition Review

| Day | Task |
|-----|------|
| **Day 218 (Mon)** | Review all CV experiments. Gather notebooks, weights, and submission files. |
| **Day 219 (Tue)** | Document architecture choices: why ResNet vs EfficientNet? What worked? **Commit:** `Add CV architecture analysis`. |
| **Day 220 (Wed)** | Analyze dataset characteristics: class imbalance, image quality, label noise. |
| **Day 221 (Thu)** | Augmentation analysis: which augmentations helped? Document findings. **Commit:** `Add augmentation impact analysis`. |
| **Day 222 (Fri)** | Error analysis: visualize misclassified images. Identify failure patterns. |
| **Day 223 (Sat)** | Read top solutions for this competition. Note techniques you missed. |
| **Day 224 (Sun)** | Finalize CV project documentation. Update `KAGGLE_TRACKER.md`. **Commit:** `Finalize CV competition review`. |

**Week 32 GitHub Targets:** 5–7 commits.

---

# 🗓️ PHASE 9 — NLP + Transformers (Days 225–252)

---

## Week 33 — NLP Foundations

| Day | Task |
|-----|------|
| **Day 225 (Mon)** | Start the **Kaggle Natural Language Processing** course. Lesson 1: Introduction to NLP. |
| **Day 226 (Tue)** | Lesson 2: Text preprocessing: lowercasing, punctuation removal, tokenization. Practice on 3 text samples. **Commit:** `Add text preprocessing exercises`. |
| **Day 227 (Wed)** | Lesson 3: Word frequency analysis. Build a vocabulary, count vectors. |
| **Day 228 (Thu)** | TF-IDF: understand term frequency, inverse document frequency. Implement TF-IDF vectorization. **Commit:** `Add TF-IDF implementation`. |
| **Day 229 (Fri)** | Word embeddings: Word2Vec, GloVe concepts. Load pre-trained embeddings. |
| **Day 230 (Sat)** | Complete the Kaggle NLP course. Review all lessons. |
| **Day 231 (Sun)** | Build a text classification baseline using TF-IDF + Logistic Regression. Save in `courses/nlp/`. **Commit:** `Complete NLP course + baseline project`. |

**Week 33 GitHub Targets:** 5–7 commits.

---

## Week 34 — NLP Models

| Day | Task |
|-----|------|
| **Day 232 (Mon)** | Logistic Regression for NLP: tune C parameter, n-grams (unigram, bigram, trigram). |
| **Day 233 (Tue)** | Naive Bayes for text classification. Compare with Logistic Regression. **Commit:** `Add Naive Bayes vs Logistic Regression comparison`. |
| **Day 234 (Wed)** | N-grams and character-level features. Experiment with different vectorization strategies. |
| **Day 235 (Thu)** | Word embeddings in practice: use pre-trained Word2Vec/GloVe as features. Compare with TF-IDF. **Commit:** `Add word embeddings experiments`. |
| **Day 236 (Fri)** | RNN basics: understand sequential processing, hidden states. Build a simple RNN for text classification. |
| **Day 237 (Sat)** | LSTM: understand gates, long-term dependencies. Replace RNN with LSTM. Compare performance. |
| **Day 238 (Sun)** | Document traditional NLP pipeline. Create a comparison table of all methods tried. **Commit:** `Add traditional NLP models comparison`. |

**Week 34 GitHub Targets:** 5–7 commits.

---

## Week 35 — Transformers

| Day | Task |
|-----|------|
| **Day 239 (Mon)** | Attention mechanism: understand Query, Key, Value. Watch "Attention Is All You Need" explained videos. |
| **Day 240 (Tue)** | Transformer architecture: encoder, decoder, self-attention, positional encoding. Draw the architecture. **Commit:** `Add transformer architecture study`. |
| **Day 241 (Wed)** | BERT: understand pre-training (MLM, NSP) and fine-tuning. Read the BERT paper summary. |
| **Day 242 (Thu)** | Hugging Face Transformers: install `transformers` library. Load a pre-trained BERT model. **Commit:** `Add Hugging Face BERT setup`. |
| **Day 243 (Fri)** | Fine-tune BERT for text classification. Use `Trainer` API or custom PyTorch loop. |
| **Day 244 (Sat)** | Experiment with different transformer models: DistilBERT, RoBERTa, ALBERT. Compare sizes and performance. |
| **Day 245 (Sun)** | Document transformer experiments. Build a small but complete transformer-based NLP project. **Commit:** `Add transformer NLP experiment project`. |

**Week 35 GitHub Targets:** 5–7 commits.

---

## Week 36 — NLP Competition

| Day | Task |
|-----|------|
| **Day 246 (Mon)** | Join an active NLP competition. Read problem statement and data carefully. |
| **Day 247 (Tue)** | EDA: text length distributions, word clouds, class balance. **Commit:** `Add NLP competition EDA`. |
| **Day 248 (Wed)** | Baseline: TF-IDF + Logistic Regression. Submit and record score. |
| **Day 249 (Thu)** | Improve with fine-tuned BERT. Compare with TF-IDF baseline. **Commit:** `Add BERT fine-tuning for competition`. |
| **Day 250 (Fri)** | Experiment with different transformers: RoBERTa, DeBERTa. Ensemble predictions. |
| **Day 251 (Sat)** | Try advanced techniques: gradient accumulation, mixed precision, longer training. |
| **Day 252 (Sun)** | Submit best NLP solution. Document all experiments. Update `KAGGLE_TRACKER.md`. **Commit:** `Complete NLP competition`. |

**Week 36 GitHub Targets:** 5–7 commits.

---

# 🗓️ PHASE 10 — Advanced Competitions (Days 253–280)

---

## Week 37 — Time Series

| Day | Task |
|-----|------|
| **Day 253 (Mon)** | Time series fundamentals: stationarity, trend, seasonality, autocorrelation. |
| **Day 254 (Tue)** | Time-series validation: walk-forward validation, purged CV. Why random split fails. **Commit:** `Add time-series validation guide`. |
| **Day 255 (Wed)** | Lag features: create lag-1, lag-7, lag-30 features. Practice on a time-series dataset. |
| **Day 256 (Thu)** | Rolling statistics: rolling mean, rolling std, expanding mean. **Commit:** `Add lag and rolling feature engineering`. |
| **Day 257 (Fri)** | Time-series models: ARIMA, Prophet, or tree-based with time features. Build a baseline. |
| **Day 258 (Sat)** | Advanced time features: day of week, month, quarter, holidays. Encode cyclical features (sin/cos). |
| **Day 259 (Sun)** | Document time-series feature engineering toolkit. Save reusable functions. **Commit:** `Add time-series feature engineering toolkit`. |

**Week 37 GitHub Targets:** 5–7 commits.

---

## Week 38 — Time Series Competition

| Day | Task |
|-----|------|
| **Day 260 (Mon)** | Join a time-series forecasting competition. Understand the forecasting horizon and granularity. |
| **Day 261 (Tue)** | EDA: plot time series, decompose trend/seasonality, check for gaps. **Commit:** `Add time-series competition EDA`. |
| **Day 262 (Wed)** | Build a baseline: naive forecast (last value), moving average. Submit. |
| **Day 263 (Thu)** | Feature engineering: lags, rolling stats, date features. Train a tree-based model. **Commit:** `Add time-series tree-based model`. |
| **Day 264 (Fri)** | Try a second approach: linear regression with time features, or ARIMA/Prophet. |
| **Day 265 (Sat)** | Ensemble time-series models. Compare blending strategies. |
| **Day 266 (Sun)** | Final submission. Document time-aware validation approach. **Commit:** `Complete time-series competition`. |

**Week 38 GitHub Targets:** 5–7 commits.

---

## Week 39 — Advanced Feature Engineering

| Day | Task |
|-----|------|
| **Day 267 (Mon)** | Target encoding: implementation, smoothing, regularization. When to use, when to avoid. |
| **Day 268 (Tue)** | Frequency encoding, count encoding, mean encoding. Compare encoding strategies. **Commit:** `Add advanced encoding techniques`. |
| **Day 269 (Wed)** | Interaction features: automated feature interactions, polynomial features. |
| **Day 270 (Thu)** | Aggregation features: group-by statistics, window aggregations. **Commit:** `Add interaction and aggregation features`. |
| **Day 271 (Fri)** | Leakage detection: identify and prevent target leakage, temporal leakage. Case studies. |
| **Day 272 (Sat)** | Build a reusable feature engineering toolkit: modular functions for encoding, interactions, aggregations. |
| **Day 273 (Sun)** | Test toolkit on a competition dataset. Document usage. **Commit:** `Add reusable feature engineering toolkit`. |

**Week 39 GitHub Targets:** 5–7 commits.

---

## Week 40 — Advanced Competition

| Day | Task |
|-----|------|
| **Day 274 (Mon)** | Choose a difficult active competition. Set a goal: "Can I consistently outperform my baseline?" |
| **Day 275 (Tue)** | Deep EDA. Understand every feature. Research the domain (medical, financial, etc.). **Commit:** `Add advanced competition deep EDA`. |
| **Day 276 (Wed)** | Build a strong baseline with everything you've learned: proper validation, good features, tuned model. |
| **Day 277 (Thu)** | Run 5 controlled experiments. Change one thing at a time. Track everything. **Commit:** `Add advanced competition experiments 1-5`. |
| **Day 278 (Fri)** | Run 5 more experiments. Focus on feature engineering and model diversity. |
| **Day 279 (Sat)** | Build an ensemble of your best models. Optimize blending weights. |
| **Day 280 (Sun)** | Submit. Document the full journey. **Commit:** `Add advanced competition submission`. |

**Week 40 GitHub Targets:** 5–7 commits.

---

# 🗓️ PHASE 11 — Kaggle Community + Reproducibility (Days 281–308)

---

## Week 41 — Publishing Notebooks

| Day | Task |
|-----|------|
| **Day 281 (Mon)** | Study 5 top-voted Kaggle notebooks. What makes them great? Structure, explanations, visuals? |
| **Day 282 (Tue)** | Plan Notebook 1: choose a dataset and a clear narrative. Outline: Problem → EDA → Approach → Model → Evaluation → Insights. |
| **Day 283 (Wed)** | Write Notebook 1: focus on storytelling, not just code. Add markdown explanations every 3–5 code cells. **Commit:** `Draft Kaggle notebook 1`. |
| **Day 284 (Thu)** | Polish Notebook 1: add visualizations, conclusions, and actionable insights. |
| **Day 285 (Fri)** | Publish Notebook 1 on Kaggle. Share in discussions or social media. **Commit:** `Publish Kaggle notebook 1`. |
| **Day 286 (Sat)** | Plan and draft Notebook 2 on a different topic. |
| **Day 287 (Sun)** | Publish Notebook 2. Update `KAGGLE_TRACKER.md`. **Commit:** `Publish Kaggle notebook 2`. |

**Week 41 GitHub Targets:** 5–7 commits.

---

## Week 42 — Notebook Quality

| Day | Task |
|-----|------|
| **Day 288 (Mon)** | Review your published notebooks. Ask: Are they reproducible? Can someone run them end-to-end? |
| **Day 289 (Tue)** | Improve Notebook 1: better explanations, cleaner code, better visualizations. Republish. **Commit:** `Polish notebook 1`. |
| **Day 290 (Wed)** | Improve Notebook 2: same quality standards. Republish. |
| **Day 291 (Thu)** | Plan Notebook 3: target a trending dataset or technique. **Commit:** `Draft Kaggle notebook 3`. |
| **Day 292 (Fri)** | Write Notebook 3 with advanced techniques (ensembling, feature engineering). |
| **Day 293 (Sat)** | Plan Notebook 4: a tutorial-style notebook teaching a concept. |
| **Day 294 (Sun)** | Publish Notebooks 3 and 4. **Commit:** `Publish notebooks 3 and 4`. |

**Week 42 GitHub Targets:** 5–7 commits.

---

## Week 43 — Kaggle Discussions

| Day | Task |
|-----|------|
| **Day 295 (Mon)** | Read 10 discussion threads from active competitions. Note common questions and expert answers. |
| **Day 296 (Tue)** | Read 5 more threads focused on validation strategies. Document insights in `notes/discussion-insights.md`. **Commit:** `Add validation strategy insights from discussions`. |
| **Day 297 (Wed)** | Read 5 threads on feature engineering techniques. Document novel ideas. |
| **Day 298 (Thu)** | Participate: ask one thoughtful question in a competition discussion. **Commit:** `Add feature engineering insights from discussions`. |
| **Day 299 (Fri)** | Participate: answer one beginner's question helpfully. |
| **Day 300 (Sat)** | Write a discussion post sharing a technique you learned. Keep it concise and valuable. |
| **Day 301 (Sun)** | Review all discussion insights. Organize into a personal knowledge base. **Commit:** `Organize discussion insights into knowledge base`. |

**Week 43 GitHub Targets:** 5–7 commits.

---

## Week 44 — Reproducibility

| Day | Task |
|-----|------|
| **Day 302 (Mon)** | Study reproducible ML projects. What do they contain? README, requirements, src/, notebooks/, .gitignore. |
| **Day 303 (Tue)** | Create a project template: `README.md`, `requirements.txt`, `src/`, `notebooks/`, `.gitignore`, `experiments/`. **Commit:** `Add reproducible project template`. |
| **Day 304 (Wed)** | Refactor one of your competition projects into the template. Separate data loading, preprocessing, modeling into `src/` modules. |
| **Day 305 (Thu)** | Add `requirements.txt` with exact versions. Test in a fresh virtual environment. **Commit:** `Refactor competition project for reproducibility`. |
| **Day 306 (Fri)** | Add a comprehensive `README.md`: problem, approach, how to run, results, file structure. |
| **Day 307 (Sat)** | Add experiment logging: save configs, metrics, and predictions for every run. |
| **Day 308 (Sun)** | Test: ask yourself, "Can someone else clone this and reproduce my results?" Fix any issues. **Commit:** `Finalize reproducible project structure`. |

**Week 44 GitHub Targets:** 5–7 commits.

---

# 🗓️ PHASE 12 — Medal-Focused Competition Strategy (Days 309–336)

---

## Week 45 — Competition Strategy

| Day | Task |
|-----|------|
| **Day 309 (Mon)** | Study leaderboard behavior: public vs private splits, shake-up, overfitting the public LB. |
| **Day 310 (Tue)** | Read about validation leakage in competitions. Case studies of famous leaks. **Commit:** `Add leaderboard and leakage strategy notes`. |
| **Day 311 (Wed)** | Study ensemble strategies from past competition solutions. When to ensemble, how many models. |
| **Day 312 (Thu)** | Choose a serious competition to target for a medal. Set a realistic goal (Bronze first). **Commit:** `Add medal competition strategy plan`. |
| **Day 313 (Fri)** | Deep dive into the competition data. Domain research. Read all discussions. |
| **Day 314 (Sat)** | Build a solid validation framework. Trust your CV more than public LB. |
| **Day 315 (Sun)** | Build your baseline. Document expected CV and LB ranges. **Commit:** `Add medal-target competition baseline`. |

**Week 45 GitHub Targets:** 5–7 commits.

---

## Week 46 — Controlled Experiments

| Day | Task |
|-----|------|
| **Day 316 (Mon)** | Set up an experiment tracking system. Use a spreadsheet or MLflow. Define your experiment format. |
| **Day 317 (Tue)** | Experiment 1–3: test 3 different feature engineering ideas. One change per experiment. **Commit:** `Add experiments E01-E03`. |
| **Day 318 (Wed)** | Experiment 4–6: test 3 different models or hyperparameters. |
| **Day 319 (Thu)** | Experiment 7–10: test preprocessing variations, encoding strategies, imputation methods. **Commit:** `Add experiments E04-E10`. |
| **Day 320 (Fri)** | Experiment 11–15: advanced techniques (target encoding, interactions, external data). |
| **Day 321 (Sat)** | Experiment 16–20: ensemble variations, blending weights, stacking configurations. **Commit:** `Add experiments E11-E20`. |
| **Day 322 (Sun)** | Review all 20+ experiments. Identify the top 5 improvements. Document why they worked. **Commit:** `Analyze all experiments and identify top improvements`. |

**Week 46 GitHub Targets:** 5–7 commits.

---

## Week 47 — Ensembling

| Day | Task |
|-----|------|
| **Day 323 (Mon)** | Select your top 3–5 single models based on CV scores and diversity. |
| **Day 324 (Tue)** | Build a simple average ensemble. Compare CV with best single model. **Commit:** `Add simple average ensemble`. |
| **Day 325 (Wed)** | Build a weighted average ensemble. Optimize weights using CV. |
| **Day 326 (Thu)** | Build a stacking ensemble. Train a meta-learner on out-of-fold predictions. **Commit:** `Add weighted average and stacking ensembles`. |
| **Day 327 (Fri)** | Compare all ensemble methods. Select the best based on CV stability. |
| **Day 328 (Sat)** | Final ensemble tuning: add/remove models, adjust weights, test robustness. |
| **Day 329 (Sun)** | Lock your final ensemble. Document the full pipeline. **Commit:** `Finalize competition ensemble`. |

**Week 47 GitHub Targets:** 5–7 commits.

---

## Week 48 — Competition Finish

| Day | Task |
|-----|------|
| **Day 330 (Mon)** | Review your best submission. Double-check for bugs, data leakage, or format errors. |
| **Day 331 (Tue)** | Run final validation: ensure your CV and LB are aligned. No surprises expected. |
| **Day 332 (Wed)** | Generate final predictions. Triple-check submission format matches competition requirements. **Commit:** `Generate final competition submission`. |
| **Day 333 (Thu)** | Submit your strongest solution. Do NOT submit anything untested. |
| **Day 334 (Fri)** | Wait for results. Meanwhile, start documenting your full solution write-up. |
| **Day 335 (Sat)** | Write a detailed solution post (even if private). Include: EDA, feature engineering, models, ensemble, CV strategy. |
| **Day 336 (Sun)** | Results day. Update `KAGGLE_TRACKER.md`. Celebrate your progress. Plan next steps. **Commit:** `Complete medal-target competition`. |

**Week 48 GitHub Targets:** 5–7 commits.

---

# 🗓️ PHASE 13 — Expert Portfolio + Long-Term Mastery (Days 337–364)

---

## Week 49 — Portfolio Cleanup

| Day | Task |
|-----|------|
| **Day 337 (Mon)** | Audit your entire `kaggle-journey/` repository. List all folders and files. |
| **Day 338 (Tue)** | Delete or archive broken notebooks. Fix any that don't run. **Commit:** `Clean broken notebooks`. |
| **Day 339 (Wed)** | Remove unnecessary files (large datasets, temp files). Update `.gitignore` if needed. |
| **Day 340 (Thu)** | Improve all `README.md` files. Add clear descriptions, results, and how-to-run instructions. **Commit:** `Improve README files across all projects`. |
| **Day 341 (Fri)** | Add experiment results summaries to each competition folder. |
| **Day 342 (Sat)** | Add project descriptions to main `README.md`. Create a visual portfolio overview. |
| **Day 343 (Sun)** | Final repository review. Ensure everything is organized and professional. **Commit:** `Finalize repository cleanup`. |

**Week 49 GitHub Targets:** 5–7 commits.

---

## Week 50 — Kaggle Profile

| Day | Task |
|-----|------|
| **Day 344 (Mon)** | Update your Kaggle bio. Write a compelling summary of your ML journey and strengths. |
| **Day 345 (Tue)** | Update profile information: location, job title, links. Add your GitHub link. |
| **Day 346 (Wed)** | Review your competition history. Ensure all competitions are documented. |
| **Day 347 (Thu)** | Curate your notebook portfolio. Pin your best 5 notebooks to your profile. |
| **Day 348 (Fri)** | Review your discussion participation. Ensure your contributions are valuable. |
| **Day 349 (Sat)** | Add a professional profile photo if you haven't already. |
| **Day 350 (Sun)** | Final profile review. Ask: "Does this profile clearly communicate my ML strengths?" **Commit:** `Update Kaggle profile and portfolio`. |

**Week 50 GitHub Targets:** 5–7 commits.

---

## Week 51 — Expert-Level Competition

| Day | Task |
|-----|------|
| **Day 351 (Mon)** | Choose one challenging active competition. Research the problem domain thoroughly. |
| **Day 352 (Tue)** | Plan your approach: research → EDA → Feature Engineering → Modeling → Validation → Ensembling → Error Analysis. |
| **Day 353 (Wed)** | Execute Phase 1: Deep research and EDA. **Commit:** `Add expert competition research and EDA`. |
| **Day 354 (Thu)** | Execute Phase 2: Feature engineering and baseline modeling. |
| **Day 355 (Fri)** | Execute Phase 3: Advanced modeling and validation. **Commit:** `Add expert competition modeling phase`. |
| **Day 356 (Sat)** | Execute Phase 4: Ensembling and error analysis. |
| **Day 357 (Sun)** | Submit and document. Work like a competition practitioner, not a beginner. **Commit:** `Submit expert-level competition`. |

**Week 51 GitHub Targets:** 5–7 commits.

---

## Week 52 — Annual Review

| Day | Task |
|-----|------|
| **Day 358 (Mon)** | Count Kaggle courses completed. Fill in: `___`. |
| **Day 359 (Tue)** | Count competitions entered. Fill in: `___`. Document best rank. |
| **Day 360 (Wed)** | Count notebooks published. Fill in: `___`. Note best-voted notebooks. |
| **Day 361 (Thu)** | Count datasets created. Fill in: `___`. |
| **Day 362 (Fri)** | Count medals earned. Fill in: `___`. Document medal types and competitions. |
| **Day 363 (Sat)** | GitHub audit: count repositories, ML projects, total commits, stars received. |
| **Day 364 (Sun)** | **FINAL DAY:** Write your annual retrospective. What did you achieve? What will you do differently next year? Update your skills bar chart. Celebrate your journey. **Commit:** `Complete 52-week Kaggle Expert journey`. |

**Week 52 GitHub Targets:** 5–7 commits.

---

# 📊 52-Week Summary Tracker

Fill this in at the end of Week 52:

## Kaggle

```
Courses completed: ___
Competitions: ___
Published notebooks: ___
Datasets: ___
Medals: ___
Best rank: ___
Discussion posts: ___
```

## GitHub

```
Total repositories: ___
ML projects: ___
Kaggle projects: ___
Total commits: ___
Stars received: ___
```

## Skills Self-Assessment

```
Python                 ██████████ 10/10
NumPy                  ██████████ 10/10
Pandas                 ██████████ 10/10
Visualization          █████████░  9/10
Scikit-learn           █████████░  9/10
Feature Engineering    ████████░░  8/10
XGBoost/LightGBM       ████████░░  8/10
Deep Learning          ███████░░░  7/10
Computer Vision        ██████░░░░  6/10
NLP                    ██████░░░░  6/10
Transformers           █████░░░░░  5/10
Competition Strategy   █████░░░░░  5/10
Ensembling             █████░░░░░  5/10
```

---

# 🔥 Daily Commit Rule

> **Commit something meaningful every single day.**

Your commit message should answer: *"What did I learn or build today?"*

**Good examples:**
- `Add Titanic EDA with survival rate analysis`
- `Implement 5-fold cross-validation for House Prices`
- `Complete Kaggle Feature Engineering course`
- `Add BERT fine-tuning notebook for NLP competition`

**Bad examples:**
- `update`
- `fix`
- `day 1`

---

# 🚀 Final Reminder

Your goal is **not**:
```
Kaggle → Random competitions
GitHub → Random commits
Courses → Certificates
Projects → Random projects
```

Your goal **is**:
```
Kaggle Courses
      ↓
Learning
      ↓
Practice
      ↓
Competitions
      ↓
Experiments
      ↓
GitHub Version Control
      ↓
Projects
      ↓
Portfolio
      ↓
AI/ML Career
```

**Kaggle teaches you → Competitions test you → GitHub records you → Projects prove you.**

> *"The only way to become a Kaggle Expert is to show up every day and do the work."*

---

*Generated from your 52-Week Kaggle Roadmap — Day-by-Day Edition*
*Total Days: 364 | Total Weeks: 52 | Phases: 13*

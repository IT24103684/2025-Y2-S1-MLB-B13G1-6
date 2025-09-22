# 2025-Y2-S1-MLB-B13G1-6-
Classifying Snakes as Venomous or Non-Venomous Using AI/ML

# Sri Lanka Institute of Information Technology

**IT2011 -- Artificial Intelligence and Machine Learning**

**Year 2 Semester 1 (2025) -- Group Assignment**

**Data Preprocessing & EDA**

**Group ID:**

**[2025-Y2-S1-MLB-B13G1-6-]{.underline}**

---

**[Repository Layout]{.underline}**

2025-Y2-S1-MLB-B13G1-6-/

│  
├── README.md                 # Project overview  
│  
├── data/  
│   ├── raw/                  # Original dataset (Venom and Non-Venom images)  
│  
├── notebooks/  
│   ├── IT24103806_Handling_class_imbalance.ipynb  
│   ├── IT24103684_Label_Encoding.ipynb  
│   ├── IT24103767_Data_cleaning.ipynb  
│   ├── IT24103653_Normalization_&_Resizing.ipynb  
│   ├── IT24103788_Data_Augmentation.ipynb  
│   ├── IT24103812_Feature_Extraction_&_Dimensionality_Reduction.ipynb  
│   └── group_pipeline.ipynb   # Combined pipeline (full workflow)  
│  
└── results/  
    ├── eda_visualizations/    # PNG charts/plots  
    └── outputs/               # Final processed datasets & trained model  

---

**[Group Members]{.underline}**

------------------------------------------------------------------------
Member ID      Name                     Preprocessing Technique  
-------------- ------------------------ --------------------------------  
IT24103806     Peiris P.V.T.D           Handling Class Imbalance  
IT24103684     Pehesara W.A.C*          Label Encoding  
IT24103767     Edirisinghe A.U          Data Cleaning  
IT24103653     Rodrigo H.A.D.A          Normalization & Resizing  
IT24103788     Gihen H.S                Data Augmentation  
IT24103812     Samarasekara K.S         Feature Extraction & Dimensionality Reduction  
------------------------------------------------------------------------

---

**[Project Overview]{.underline}**

Snakes are often killed on sight because people cannot distinguish between venomous and non-venomous species. This fear-driven behavior harms wildlife and endangers people during snake encounters or medical emergencies after bites.  

In this project, **Classifying Snakes as Venomous or Non-Venomous Using AI/ML**, we develop a **binary classification model** trained on snake images. The model analyzes visual features such as **color patterns, head shape, texture, and scale arrangements** to classify whether a snake is venomous.  

**Goals:**  
- Provide an **easy-to-use AI/ML tool** for quick and accurate classification.  
- Assist **medical professionals** with immediate diagnosis and treatment.  
- Support **mobile deployment** in remote, resource-limited regions.  
- Improve **epidemiological data collection** on snakebites.  

---

**[Dataset Details]{.underline}**

- **Main Dataset:** Venom and Non-Venom Snake Images  
- **Source:** [Kaggle](https://www.kaggle.com/datasets/lephanvanviet/venom-and-nonvenom/data)  
- **Records:** ~9,200 images  
- **Features:**  
  - Raw snake images (visual attributes: color, shape, texture, scale patterns)  
  - Target: Binary class — `"Venomous"` vs `"Non-Venomous"`  
- **Preprocessing:**  
  - Image resizing, normalization, augmentation  
- **Independence:**  
  - No reliance on geographical data, ensuring broad global applicability  

---

**[Preprocessing Techniques Applied]{.underline}**

1. Handling Class Imbalance — Balanced dataset through augmentation and resampling.  
2. Label Encoding — Converted class labels into binary numeric form.  
3. Data Cleaning — Removed corrupted, duplicate, or mislabeled images.  
4. Normalization & Resizing — Standardized image size and scaled pixel values.  
5. Data Augmentation — Applied flips, rotations, zoom, and brightness shifts.  
6. Feature Extraction & Dimensionality Reduction — Extracted deep features and applied PCA for noise reduction.  

---

**[How to run code]{.underline}**

1. Clone or download this repository.  
2. Upload dataset to Google Drive.  
3. Open notebooks in `notebooks/` and run them sequentially.  
4. Use `group_pipeline.ipynb` to run the complete preprocessing and training workflow.  
5. Final processed dataset be saved in `Data_Snakes_processed_jpg/` with CSV labels file in 'Data_Snakes_processed_jpg/labels.csv'.  
6. Visualizations (EDA, augmented samples) will be automatically saved in `results/eda_visualizations/`.  

---


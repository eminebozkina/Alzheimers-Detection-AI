# Integrating MRI Imaging and Biomarkers for the Early Detection of Alzheimer’s Disease through AI
This repository contains the MSc dissertation project by Emine Bozkina, supervised by Professor Miroslaw Bober at the University of Surrey. The project focuses on integrating MRI imaging and biomarkers using AI techniques for the early detection of Alzheimer’s disease.

## Overview
The goal of this project is to develop a machine learning model that utilizes multimodal data, including MRI scans and biomarker information, to improve the accuracy of early Alzheimer’s disease diagnosis.

---

## Aims and Objectives
- To explore the role of AI in early diagnosis and prognosis of Alzheimer’s disease.
- To design and implement a CNN-LSTM hybrid model for multimodal data analysis.
- To evaluate the model's performance using metrics such as accuracy, loss, and ROC curves.

---

## Data Sources
- MRI and biomarker data were obtained from the **Alzheimer’s Disease Neuroimaging Initiative (ADNI)**.
- References to key studies and datasets:
  1. *Artificial intelligence-based diagnosis of Alzheimer's disease with brain MRI images* - Yao et al., 2023.
  2. *Comparison of machine learning-based approaches to predict the conversion to Alzheimer’s disease* - Franciotti et al., 2023.
  3. *Revolutionizing the early detection of Alzheimer’s disease through non-invasive biomarkers* - Vrahatis et al., 2023.
  4. *Use of multimodality imaging and artificial intelligence for diagnosis and prognosis of early stages of Alzheimer's disease* - Liu et al., 2018.
  5. *The Alzheimer’s Disease Neuroimaging Initiative (ADNI): MRI methods* - Jack Jr et al., 2008.

---

## Project Design
- A hybrid **CNN-LSTM model** was designed:
  - **CNN (Convolutional Neural Network):** Processes MRI imaging data for spatial feature extraction.
  - **LSTM (Long Short-Term Memory):** Processes biomarker data for temporal and sequential analysis.
- Model evaluation was performed using metrics such as accuracy, loss trends, and ROC curves.


## Results
### Model Performance
- **Accuracy:** High predictive accuracy achieved for early detection.
- **Loss Trends:** Stable loss values after 10 epochs.
- **ROC Curve:** Achieved robust AUC values demonstrating reliable performance.

### Key Insights
- Multimodal data integration significantly enhances diagnostic accuracy.
- Hybrid CNN-LSTM architecture is effective for Alzheimer’s detection.

---

## Technologies Used
- **Programming Languages:** Python
- **Libraries and Frameworks:** TensorFlow, Keras, NumPy, Pandas
- **Data Sources:** ADNI
- **Machine Learning Models:** CNN, LSTM

---

## Future Works
- Expanding the dataset for broader applicability.
- Exploring other multimodal data sources, such as PET scans.
- Enhancing the interpretability of the model for clinical applications.

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/alzheimers-detection-ai.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the model:
   ```bash
   python main.py
   ```

---

## References
1. Yao, Z., et al. (2023). Artificial intelligence-based diagnosis of Alzheimer's disease with brain MRI images. *European Journal of Radiology*.
2. Franciotti, R., et al. (2023). Comparison of machine learning-based approaches to predict the conversion to Alzheimer’s disease. *Neuroscience*.
3. Vrahatis, A.G., et al. (2023). Revolutionizing the early detection of Alzheimer’s disease through non-invasive biomarkers. *Sensors*.
4. Liu, X., et al. (2018). Use of multimodality imaging and artificial intelligence for diagnosis and prognosis of early stages of Alzheimer's disease. *Translational Research*.
5. Jack Jr, C.R., et al. (2008). The Alzheimer’s Disease Neuroimaging Initiative (ADNI): MRI methods. *Journal of Magnetic Resonance Imaging*.

---

## Contact
If you have any questions or suggestions, please contact me at [eminebozkina@gmail.com](mailto:eminebozkina@gmail.com).

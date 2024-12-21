**EEG Data Analysis and Alcoholism Detection**

This project focuses on analyzing EEG (electroencephalogram) data to classify subjects as alcoholic or control using signal processing and machine learning techniques.

📂 **Dataset Overview**

The EEG dataset consists of signals recorded from multiple electrodes over time for two groups:

•	**Alcoholic Group**

•	**Control Group**

Each sample represents brain activity captured over time, providing insights into neural patterns associated with alcoholism.

🔧 **Approach**

**1. Signal Processing**

•		Analyze EEG data for classifying subjects into alcoholic and control groups according to subject experimented each electrode channel sensor value; sampled at 256 Hz.


**2. Visualization**

•	Plotted the original EEG signals, wavelet scaleograms, and Fourier Transform power spectra to gain insights into how EEG patterns differ between alcoholic and control subjects.

**3. Machine Learning**

**•	K-Nearest Neighbors (KNN):** Trained on the EEG data to classify subjects into alcoholic and control groups.

**•	Support Vector Machine (SVM):** Used to improve classification accuracy by leveraging the distinct EEG features in both groups.

**⚙️ Technologies Used**

•	Python (NumPy, pandas, Matplotlib, PyWavelets, SciPy, Scikit-learn)
•	Signal Processing Techniques (CWT, FFT)
•	Machine Learning (KNN, SVM)

**📝 Results**

**•	KNN Classifier:** Achieved a high classification accuracy (~99%), with strong recall and precision for both groups.
**•	SVM Classifier:** Further improved classification, achieving reliable separation of alcoholic and control subjects based on EEG features.
**📊 Visualizations**
•	EEG signals, wavelet scaleograms, and Fourier Transform power spectra are all included in the project to aid in understanding how EEG patterns relate to alcoholism.

•	EEG signals, wavelet scaleograms, and Fourier Transform power spectra are all included in the project to aid in understanding how EEG patterns relate to alcoholism.


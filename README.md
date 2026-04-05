## Key Concepts
- Ballistocardiography (BCG)  
- Time-frequency analysis  
- Continuous Wavelet Transform (CWT)  
- Autocorrelation function  
- Peak detection in physiological signals  

---

##  Technologies Used
- Python  
- NumPy  
- SciPy  
- Matplotlib  
- PyWavelets (if used)  
- Jupyter Notebook  

---
---

## Methodology

### 1. Signal Acquisition
- Load BCG signal as a time-series dataset  
- Represents body micro-movements caused by cardiac activity  

### 2. Preprocessing
- Noise reduction and smoothing  
- Signal normalization  

### 3. Continuous Wavelet Transform (CWT)
- Convert signal into time-frequency domain  
- Enhance heartbeat-related features  
- Improve signal clarity under noise  

### 4. Autocorrelation Analysis
- Compute autocorrelation of processed signal  
- Identify periodic patterns  
- Extract dominant heart rate frequency  

### 5. Heart Rate Estimation
- Convert detected periodicity into BPM (beats per minute)  

### 6. Visualization
- Plot original signal  
- Plot transformed signal (CWT)  
- Highlight detected peaks / periodic intervals  

---

##  Results
- Robust heart rate estimation from BCG signals  
- Improved detection accuracy using CWT preprocessing  
- Effective handling of noisy physiological data  

---

##  Challenges
- Sensitivity to motion artifacts  
- Selection of optimal wavelet scales  
- Noise in real-world BCG signals  

---

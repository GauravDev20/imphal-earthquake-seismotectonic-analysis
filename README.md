# Seismotectonic Analysis of the 2016 Imphal Earthquake

## 📌 Project Overview

This project presents a **seismotectonic analysis of the 2016 Imphal Earthquake (Mw 6.7)** using **Python, PyGMT, and Google Colab**.

The project focuses on spatial visualization and statistical analysis of the earthquake sequence, including earthquake distribution, seismic depth variation, focal mechanisms, seismic waveforms, and empirical earthquake-sequence relationships.

---

## 🎯 Objectives

The main objectives of this project were to:

* Visualize the **Mw 6.7 Imphal Earthquake mainshock**
* Analyze the spatial and depth distribution of earthquakes in the Imphal region
* Generate a **seismic cross-section** to examine earthquake depth distribution
* Visualize **GCMT focal mechanism solutions**
* Analyze the seismic waveform of the mainshock
* Study aftershock decay using **Omori's Law**
* Analyze earthquake frequency–magnitude distribution using the **Gutenberg–Richter Law**
* Evaluate the earthquake sequence using **Bath's Law**

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Mapping & Visualization:** PyGMT
* **Seismic Analysis:** ObsPy
* **Data Analysis:** Pandas
* **Plotting:** Matplotlib
* **Environment:** Google Colab
* **Data Sources/Products:** Earthquake catalogue and GCMT focal mechanism data

---

## 🗺️ Spatial & Seismotectonic Analysis

### Mainshock Mapping

A regional map was generated to visualize the **2016 Imphal Earthquake mainshock (Mw 6.7)** along with major surrounding cities and regional topography.

### Earthquake Distribution

Earthquake events from **5 September 2015 to 2 May 2016** were mapped according to their magnitude and depth to examine the spatial distribution of seismicity around the Imphal region.

### Seismic Cross-Section

A seismic cross-section was generated to visualize the variation of earthquake depth with distance and examine the subsurface distribution of seismicity.

### GCMT Focal Mechanisms

GCMT focal mechanism solutions were mapped across the region to visualize the earthquake source mechanisms and their spatial distribution.

---

## 📈 Seismic Waveform Analysis

The seismic waveform of the **Mw 6.7 mainshock** was analyzed using three components:

* BHZ – Vertical
* BHN – North
* BHE – East

The waveform was examined to visualize the seismic signal and its temporal characteristics.

---

## 📊 Statistical Earthquake Analysis

### Omori's Law

The temporal decay of aftershock activity following the mainshock was analyzed using **Omori's Law**.

**Estimated parameter:**

* **p-value = 0.03**

The observed earthquake sequence was compared with the fitted Omori relationship.

---

### Gutenberg–Richter Law

The frequency–magnitude relationship of the earthquake sequence was analyzed using the **Gutenberg–Richter Law**.

**Estimated b-value:**

* **b = 0.55**

A magnitude-versus-frequency distribution was also generated to examine the seismicity characteristics of the earthquake sequence.

---

### Bath's Law

Bath's Law was evaluated by comparing the magnitude of the mainshock with the largest aftershock.

**Results:**

* Mainshock: **Mw 6.70**
* Largest aftershock: **Mw 4.70**
* ΔM = **2.00**

The calculated ΔM was greater than the commonly expected value of 1.2, indicating that the analyzed sequence **does not follow Bath's Law**.

---

## 📊 Key Results

| Analysis            |        Result |
| ------------------- | ------------: |
| Mainshock Magnitude |    **Mw 6.7** |
| Omori's Law         |  **p = 0.03** |
| Gutenberg–Richter   |  **b = 0.55** |
| Largest Aftershock  |   **Mw 4.70** |
| Bath's Law          | **ΔM = 2.00** |

---

## 📁 Project Structure

```text
imphal-earthquake-seismotectonic-analysis/
│
├── Imphal_Earthquake_Seismotectonic_Analysis.ipynb
├── figures/
│   ├── mainshock_map.png
│   ├── earthquake_distribution.png
│   ├── seismic_cross_section.png
│   ├── focal_mechanisms.png
│   ├── seismic_waveform.png
│   ├── omoris_law.png
│   ├── gutenberg_richter.png
│   └── baths_law.png
│
└── README.md
```

---

## ▶️ How to Run

The complete workflow was developed in **Google Colab**.

### 1. Open the notebook

Open:

`Imphal_Earthquake_Seismotectonic_Analysis.ipynb`

### 2. Install required packages

```python
!apt-get install -y gmt ghostscript
!pip install pygmt==0.14.0 obspy pandas matplotlib
```

### 3. Run the notebook

Execute the cells sequentially or use **Run All** in Google Colab.

---

## 📌 Key Takeaways

* Developed a complete **Python-based seismotectonic analysis workflow**.
* Used **PyGMT** for regional earthquake and geological visualization.
* Analyzed earthquake spatial and depth distributions.
* Integrated **GCMT focal mechanisms** into regional seismicity analysis.
* Applied **Omori's Law, Gutenberg–Richter Law, and Bath's Law** to characterize the earthquake sequence.
* Performed seismic waveform visualization using three-component data.

---

## 👨‍💻 Author

**Gaurav Dev**
M.Tech, IIT Kanpur
Department of Earth Science

---

## 📚 Project Type

**Seismology | Seismotectonics | Earthquake Analysis | Geospatial Visualization | PyGMT**

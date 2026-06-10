#  Indoor Air Quality - IAQ- Dataset Schools San Luis Potosi-Mexico



## I) Description 


This paper presents one of the first experimental indoor air quality (IAQ) datasets collected in the San Luis Potos´ı Metropolitan Area, a dusty semi-arid region characterized by rapid urban growth and industrial activity. The dataset, distributed in a semicolon-separated text format, was acquired during a longitudinal monitoring campaign conducted between October 2023 and June 2024 in public elementary schools exposed to multiple IAQ-related environmental stressors. The dataset contains 174260 records collected at an average sampling interval of 10 minutes using an Internet of Things (IoT)-based monitoring infrastructure.

Each record includes: (i) the context information including the timestamp and the identifier of the sensing node associated with the monitored classroom; (ii) indoor particulate matter concentration, expressed as PM2.5 mass concentration (µg/m3); (iii) carbon dioxide (CO2) concentration; (iv) complementary environmental variables, namely air temperature and relative humidity; and (v) Pupil Health Air Quality Index (PHAQI). Beyond the dataset itself, this work provides the associated source code, metadata, and contextual information required to support data preprocessing, organization, and analysis. The accompanying resources also enable researchers to reproduce the experimental workflow and generate customized synthetic datasets for benchmarking, comparative studies, and future IAQ research applications.




## II) Specifications Table

### Subject :  
Environmental Monitoring;  Indoor Air Quality; Classification.

###  Specific subject area :  
Experimental Indoor Air Quality (IAQ) dataset collected using an IoT-based monitoring infrastructure in public elementary schools located in the San Luis Potosí Metropolitan Area, Mexico. The dataset includes time stamp, classroom identifier, PM2.5 concentration, Co2 concentration, air temperature, and relative humidity measurements.

### Data format :  
Raw; Processed.

### Type of data : 
Tabular; Semicolon-separated text files (.csv)

### Data collection:  
The experimental data collection campaign was conducted between October 2023 and June 2024 in public elementary schools situated in the San Luis Potosí Metropolitan Area, Mexico. Indoor air parameters were monitored using an IoT-based sensing infrastructure deployed inside classrooms. Measurements were collected at an average sampling interval of 10 minutes. Each IoT sensing node continuously monitored particulate matter concentration (PM2.5), carbon dioxide (CO2), air temperature, and relative humidity. The collected measurements were automatically validated, timestamped, and stored for subsequent preprocessing, sorting, and analysis.

### Data source location: 
10 classrooms in public elementary schools, San Luis Potosí Metropolitan Area, San Luis Potosí, Mexico. 

### Geographic context: 
Semi-arid urban–industrial environment. 





## III) Dataset Composition

This repository contains an Indoor Air Quality (IAQ) dataset collected through an IoT-based monitoring infrastructure deployed in a medium-sized airport environment. The dataset was designed to support data analysis, air quality assessment, and machine learning applications related to indoor environmental conditions.

The dataset consists of **174,260 observations** described by **six variables**, including four environmental parameters and two spatio-temporal descriptors:

| Parameter | Unit | Description |
|------------|------|-------------|
| Timestamp | Date-Time | Date and time of the measurement. |
| IDclass | Categorical | Classroom/monitoring location identifier used for supervised learning tasks. |
| CO₂ | ppm | Carbon dioxide concentration, commonly used as an indicator of ventilation efficiency and occupancy levels. |
| PM₂.₅ | µg/m³ | Fine particulate matter with aerodynamic diameter ≤ 2.5 µm. |
| Temperature | °C | Indoor air temperature. |
| Humidity | % | Indoor relative humidity. |
| PHAQI | Health Level | Pupil Health Air Quality Index derived from the monitored IAQ parameters. |

### Dataset Structure

The dataset combines environmental measurements with spatial and temporal information:

- **Environmental variables:** PM₂.₅, CO₂, Temperature, and Humidity.
- **Spatio-temporal variables:** `IDclass` and `Timestamp`.
- **Target variable:** `PHAQI` (Pupil Health Air Quality Index).

The following figure summarizes the levels of the PHAQI.

<p align="center">
  <img src="PHAQI-img.png" width="800">
</p>
# Indoor Air Quality - IAQ- Dataset Schools San Luis Potosi-Mexico



## I) Description 


This paper presents one of the first experimental indoor air quality (IAQ) datasets collected in the San Luis Potos´ı Metropolitan Area, a dusty semi-arid region characterized by rapid urban growth and industrial activity. The dataset, distributed in a semicolon-separated text format, was acquired during a longitudinal monitoring campaign conducted between October 2023 and June 2024 in public elementary schools exposed to multiple IAQ-related environmental stressors. The dataset contains 174260 records collected at an average sampling interval of 10 minutes using an Internet of Things (IoT)-based monitoring infrastructure.

Each record includes: (i) the context information including the timestamp and the identifier of the sensing node associated with the monitored classroom; (ii) indoor particulate matter concentration, expressed as PM2.5 mass concentration (µg/m3); (iii) carbon dioxide (CO2) concentration; (iv) complementary environmental variables, namely air temperature and relative humidity; and (v) Pupil Health Air Quality Index (PHAQI). Beyond the dataset itself, this work provides the associated source code, metadata, and contextual information required to support data preprocessing, organization, and analysis. The accompanying resources also enable researchers to reproduce the experimental workflow and generate customized synthetic datasets for benchmarking, comparative studies, and future IAQ research applications.




## II) Specifications Table

### Subject :  
Environmental Monitoring;  Indoor Air Quality; Classification.

###  Specific subject area :  
Experimental Indoor Air Quality (IAQ) dataset collected using an IoT-based monitoring infrastructure in public elementary schools located in the San Luis Potosí Metropolitan Area, Mexico. The dataset includes time stamp, classroom identifier, PM2.5 concentration, Co2 concentration, air temperature, and relative humidity measurements.

### Data format :  
Raw; Processed.

### Type of data : 
Tabular; Semicolon-separated text files (.csv)

### Data collection:  
The experimental data collection campaign was conducted between October 2023 and June 2024 in public elementary schools situated in the San Luis Potosí Metropolitan Area, Mexico. Indoor air parameters were monitored using an IoT-based sensing infrastructure deployed inside classrooms. Measurements were collected at an average sampling interval of 10 minutes. Each IoT sensing node continuously monitored particulate matter concentration (PM2.5), carbon dioxide (CO2), air temperature, and relative humidity. The collected measurements were automatically validated, timestamped, and stored for subsequent preprocessing, sorting, and analysis.

### Data source location: 
10 classrooms in public elementary schools, San Luis Potosí Metropolitan Area, San Luis Potosí, Mexico. 

### Geographic context: 
Semi-arid urban–industrial environment. 





## III) Dataset Composition

This repository contains an Indoor Air Quality (IAQ) dataset collected through an IoT-based monitoring infrastructure deployed in a medium-sized airport environment. The dataset was designed to support data analysis, air quality assessment, and machine learning applications related to indoor environmental conditions.

The dataset consists of **174,260 observations** described by **six variables**, including four environmental parameters and two spatio-temporal descriptors:

| Parameter | Unit | Description |
|------------|------|-------------|
| Timestamp | Date-Time | Date and time of the measurement. |
| IDclass | Categorical | Classroom/monitoring location identifier used for supervised learning tasks. |
| CO₂ | ppm | Carbon dioxide concentration, commonly used as an indicator of ventilation efficiency and occupancy levels. |
| PM₂.₅ | µg/m³ | Fine particulate matter with aerodynamic diameter ≤ 2.5 µm. |
| Temperature | °C | Indoor air temperature. |
| Humidity | % | Indoor relative humidity. |
| PHAQI | Health Level | Pupil Health Air Quality Index derived from the monitored IAQ parameters. |

### Dataset Structure

The dataset combines environmental measurements with spatial and temporal information:

- **Environmental variables:** PM₂.₅, CO₂, Temperature, and Humidity.
- **Spatio-temporal variables:** `IDclass` and `Timestamp`.
- **Target variable:** `PHAQI` (Pupil Health Air Quality Index).

The following figure summarizes the levels of the PHAQI.

<p align="center">
  <img src="PHAQI-img.png" width="800">
</p>

*Figure 1. Summary of the PHAQI classes*





### Dataset Statistics

| Metric | Value |
|---------|---------|
| Total Samples | 174,260 |
| Number of Features | 6 |
| Monitoring Period | 1 Year |
| Environment | Indoor Air quality in elementary schools |




---

# Dataset Authors

This dataset was developed as part of a research project on Indoor Air Quality (IAQ) monitoring and assessment in educational environments.

| Author | Affiliation | Contribution |
|----------|------------|--------------|
| Salvador Ruiz-Correa | [Instituto Potosino de Investigación Científica y Tecnológica MX, Carretera a La Presa 2055, 78216 San Luis Potosí, San Luis Potosí, Mexico] | Conceptualization, Methodology, Software, Validation, Formal Analysis, Investigation, Resources, Data Curation, Writing – Review & Editing, Project Administration, Funding Acquisition |
| Lamine Amour | [ESME Engineering school, ESME Research Lab, 38 Rue Molière, 94200 Ivry-sur-Seine, France] | Formal Analysis, Investigation, Resources, Data Preparation and Curation, Writing – Review & Editing |
| Abdulahim Dandoush | [University of Doha for Science and Technology (UDST), Al Samur Street, Doha, Qatar] | Formal Analysis, Investigation, Resources, Data Preparation and Curation, Writing – Review & Editing |
| XXX XXXXXXXX | [Institution] | Conceptualization, Methodology, Software, Validation, Formal Analysis, Investigation, Resources, Data Curation, Writing – Review & Editing, Visualization |

---

# Citation

If you use this dataset in your research, please cite:

```bibtex
@article{dataset2025,
  author  = {Author1 and Author2 and Author3},
  title   = {Indoor Air Quality Dataset for Environmental Monitoring and Machine Learning Applications},
  journal = {Data in Brief},
  year    = {2025},
  doi     = {xxxxxxxxxx}
}
```

---

# Data Availability

The complete dataset is publicly available through:

🔗 **Mendeley Data Repository**

https://doi.org/xxxxxxxxxx

---

# Acknowledgements

This work was supported by the Mexican research and innovation program under Grant Agreement No. XXXXXXX.

The authors would like to thank the participating schools and all stakeholders involved in the deployment, operation, and maintenance of the indoor air quality monitoring infrastructure. Their support was essential for the successful collection and validation of the dataset.

---

# Ethical Statement


*Figure 1. Summary of the PHAQI classes*





### Dataset Statistics

| Metric | Value |
|---------|---------|
| Total Samples | 174,260 |
| Number of Features | 6 |
| Monitoring Period | 1 Year |
| Environment | Indoor Air quality in elementary schools |




---

# Dataset Authors

This dataset was developed as part of a research project on Indoor Air Quality (IAQ) monitoring and assessment in educational environments.

| Author | Affiliation | Contribution |
|----------|------------|--------------|
| Salvador Ruiz-Correa | [Instituto Potosino de Investigación Científica y Tecnológica MX, Carretera a La Presa 2055, 78216 San Luis Potosí, San Luis Potosí, Mexico] | Conceptualization, Methodology, Software, Validation, Formal Analysis, Investigation, Resources, Data Curation, Writing – Review & Editing, Project Administration, Funding Acquisition |
| Lamine Amour | [ESME Engineering school, ESME Research Lab, 38 Rue Molière, 94200 Ivry-sur-Seine, France] | Formal Analysis, Investigation, Resources, Data Preparation and Curation, Writing – Review & Editing |
| Abdulahim Dandoush | [University of Doha for Science and Technology (UDST), Al Samur Street, Doha, Qatar] | Formal Analysis, Investigation, Resources, Data Preparation and Curation, Writing – Review & Editing |
| XXX XXXXXXXX | [Institution] | Conceptualization, Methodology, Software, Validation, Formal Analysis, Investigation, Resources, Data Curation, Writing – Review & Editing, Visualization |

---

# Citation

If you use this dataset in your research, please cite:

```bibtex
@article{dataset2025,
  author  = {Author1 and Author2 and Author3},
  title   = {Indoor Air Quality Dataset for Environmental Monitoring and Machine Learning Applications},
  journal = {Data in Brief},
  year    = {2025},
  doi     = {xxxxxxxxxx}
}
```

---

# Data Availability

The complete dataset is publicly available through:

🔗 **Mendeley Data Repository**

https://doi.org/xxxxxxxxxx

---

# Acknowledgements

This work was supported by the Mexican research and innovation program under Grant Agreement No. XXXXXXX.

The authors would like to thank the participating schools and all stakeholders involved in the deployment, operation, and maintenance of the indoor air quality monitoring infrastructure. Their support was essential for the successful collection and validation of the dataset.

---

# Ethical Statement

The dataset does not contain personal information, human subject data, animal experiments, or data collected from social media platforms.

All measurements were obtained through environmental monitoring sensors deployed in educational facilities.

---

# Limitations

The dataset was collected over a period of less than one year in selected schools within the San Luis Potosí Metropolitan Area. Consequently, some gaps in the time series may exist due to sensor maintenance, communication interruptions, or operational constraints.

Furthermore, the monitored locations were selected to represent medium-sized classrooms in elementary schools and may not fully characterize all educational environments. Future monitoring campaigns should extend the sensing infrastructure to additional locations and include complementary environmental variables such as Total Volatile Organic Compounds (TVOC), outdoor temperature, and relative humidity.

---

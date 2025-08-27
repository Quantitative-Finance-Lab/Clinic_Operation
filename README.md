# **Institution Operation Dataset**

## **Overview**
The **Institution Operation Dataset** provides comprehensive data on the operational patterns of primary healthcare institutions in South Korea. It is publicly available for download on **[Zenodo](https://zenodo.org/records/15080544)** and **[GitHub](https://github.com/Quantitative-Finance-Lab/Institution_Operation)** in **XLSX (`Institution_operation.XLSX`)** formats.

This dataset contains **44,915 observations** and **21 variables**, making it a valuable resource for researchers studying clinic survival, healthcare accessibility, and regional healthcare disparities. To enhance accessibility and citation, the dataset is assigned a **DOI**: [`10.5281/zenodo.15080544`](https://zenodo.org/records/15080544).

The dataset is released under the **MIT License**, allowing for unrestricted use, modification, and distribution, ensuring broad applicability in academic and policy research.

---

## **Data Structure**
The dataset follows a structured format to facilitate **primary healthcare institution operational research**. Each row represents a primary healthcare institution, while columns capture key attributes related to geography, institution characteristics, demographics, healthcare environment, and temporal survival data.

### **Key Variables**

- **Geographic Information:**
  - Administrative codes (`Admin`)
  - Latitude (`Latitude`) and longitude (`Longitude`)

- **Institution Characteristics:**
  - Clinic area in square meters (`Area`)
  - Number of medical professionals (`Medic`)
  - Number of wards (`Ward`) and beds (`Beds`)

- **Demographic & Healthcare Environment Factors:**
  - Hinterland population (`Population`)
  - Number of regional hospitals (`Nhos`)
  - Number of regional doctors (`Ndocs`)

- **Temporal Information:**
  - Opening and closing dates (`OpenYear`, `OpenMonth`, `OpenDay`, `CloseYear`, `CloseMonth`, `CloseDay`)
  - Censoring status (`Censored`)

- **Medical Specialties:**
  - Essential primary care services (`Essential`, binary variable)
  - Reproductive health services (`Reproductive`, binary variable)

- **Urban-Rural Classification:**
  - Urban classification (`Urban`: 1 for urban, 0 for rural)
  - Metropolitan classification (`Metropolitan`: 1 for Metropolitan, 0 for else)
  - Seoul/other greater Seoul classification ('Seoul/other greater Seoul': 1 for Seoul, 2 for other greater Seoul, 0 for else)


### **Analysis Potential**
The dataset is designed for **primary care institution operation/survival analysis**, with the **closure of primary care institution** serving as the event of interest. Researchers can use this dataset to investigate operational patterns across different primary hhcare institution types, regional disparities, and the impact of various healthcare resource factors.


---


### **Accessing the Dataset**
- **Zenodo:** [`10.5281/zenodo.15080544`](https://zenodo.org/records/15080544)
- **GitHub Repository:** [`Clinic_Operation`](https://github.com/Quantitative-Finance-Lab/Clinic_Operation)

---

## **License**
This dataset is released under the **MIT License**, allowing free use, modification, and distribution.

For any questions or collaborations, please contact **[cgh000@yonsei.ac.kr]**.

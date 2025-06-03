![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

- This project explores `Geospatial Data`, `Proximity Analysis`, `Linear Algebra`, and `Food Security Impacts` using **Python**
- The goal is to analyze the spatial relationships between food accessibility and socio-economic variables
- It also contains intense data cleaning and manipulation in `Datasets_Manipulating_and_Cleaning.ipynb`

---

## Project Overview  
- **Dataset:** Geospatial data on food security indicators  
- **Objective:** Identify spatial trends in food accessibility and evaluate economic determinants  
- **Key Methods:** Choropleth mapping, geospatial proximity analysis, regression modeling  
- **Code:** Available in `Exploratory_Data_Analysis_and_Regression_Analysis.ipynb`
- **Main Variable** `Market Access` which is a **linear transformation** of haversine distances and output of top food exporters (higher is better access to these exporters)

---

## Geospatial Analysis  
Using **GeoPandas**, food security indicators are mapped to visualize regional disparities.

**Choropleth Visualizations of Food Security Indicators** 

![Food Security](https://lh3.googleusercontent.com/pw/AP1GczMME1qfJhDQnFBW6MPp7oEtByOto4TRvW-HvM6A1xxMnNCbqv_GFKj7xYxGcOpq7Eht-feHGYSaw-p5DuoyE1GL54hdoovBqf7qg0uQNAX8x5lsumYn6fUzzqFOa9J801gTHuRaqnb-vo39nOAlb-Me=w754-h305-s-no-gm?authuser=0)
![LT of Proximity Measure](https://lh3.googleusercontent.com/pw/AP1GczP225Yk-z59HTgWA0vFD4CL7A74LtxVgiCvZ8bfc2ztLvdR2ZlBi5gXj7WUW2V1PN28XIiey-i4HVOYg1Iki9uX6uvGRZ1nBAoApLiA-qPL4gN_1XcXJE24tT8WHE50nt-BaDUiHSGrMkpmFR8qohMg=w706-h281-s-no-gm?authuser=0)
![Agri](https://lh3.googleusercontent.com/pw/AP1GczOnTw4rPtigxvNHwakKQkPXq9gwib4m5fiz5r_j4gWNizJlnICDOiZLP_Nk3UsQcE9q9TZlJNpGFarZ3vCWXIlLxomCiE9sIMR2YT8GloinqDi7fR-6NT-Bw32M2bIQGyJVI9lpWAKoD3jCsmU-pHrO=w715-h281-s-no-gm?authuser=0)
![Trade](https://lh3.googleusercontent.com/pw/AP1GczPl69oXcg6mGZXDjFUMkx9sRSmVRCtbP6v0PI8zGncA3hy07vsx_KhZhK8EKFA2cvovyqsP2KDJealyqo4bNCNsuRqpwEBXhP_HBoliHXMRVTGxiCZfifBrZfWm-JT1-V2YDdjtH9_FfwqHrcAwVm_Z=w706-h281-s-no-gm?authuser=0)
![Income](https://lh3.googleusercontent.com/pw/AP1GczPf3LDJaVvYjL5Jq_sqU6fDRMvKVAUfJJaw8tGxN4tXgOaxiHsuAeLDMyWSOxnomlNHu_U8KNdO8PSirCmpxlYVQnr3Hl8_3kZ4-zIjCDQNsLKOMu0pUeveTtbwE-qqWfdOFxC-fEK9ggioDTch0DPL=w950-h401-s-no-gm?authuser=0)

---

## Other Plots
![Scatter1](https://lh3.googleusercontent.com/pw/AP1GczOhCGzZHVuOE9YgsHF3XyTHMIb8CllhH0odpBW2vEDEfxzKWgJKYX2o10KD5GXqV97fhNwpHwC9zSSAJBr12JfHqIDKz0djioRVu8RhS0lkvtNLQS4uFsZvhrTsEUVMx0K3vcVM3YBeesdDos3k5g_K=w686-h547-s-no-gm?authuser=0)
![Scatter2](https://lh3.googleusercontent.com/pw/AP1GczOs6AKXZKsAdQPT4DxE0Ei4YKLY2vWWqVD80sg6hQmYhaoDX6KQkiCpIcirhxceF1EBc4qmQF8ul25ntqTC9RrQqTkucHPVb4WIRYc0a-E_HUOK4kzpFGoTbvy6ZC8lgP2s7_-NxDk3Ay5A3XhNuF2n=w1789-h490-s-no-gm?authuser=0)


---

## Regression Analysis  
Statistical models assess the relationship between **food security scores** and **proximity to top food exporters** using `statsmodels`.

**Regression Output & Findings**  
![Regression Results](https://lh3.googleusercontent.com/pw/AP1GczPI-sqgABdH6KWlcUbt_m89dCxX8hcjilds2VQ3jWg53bKhJm8JV53-MvgDp3n5ri3Tlio_6vG_kUQ5Hotu3A2ytKLZWk8XMWZofuhWdUmhVyA7xkvZGhs9-q9fIQMhaYmaDE_PkhnE_hpIbGT-vXaA=w856-h694-s-no-gm?authuser=0)


---
🚀 Full details in **[Exploratory_Data_Analysis_and_Regression_Analysis.ipynb](Exploratory_Data_Analysis_and_Regression_Analysis.ipynb)**  

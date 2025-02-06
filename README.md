# **Introduction to Geospatial Analysis**  

## **Overview**  
This repository contains all replication materials for the **Introduction to Geospatial Analysis** training conducted by **Taka Masaki** on **Thursday, 13 February 2025, from 1:00 PM - 2:15 PM**. The materials include scripts, datasets, and figures for hands-on geospatial analysis.  

## **Training Agenda**  

**Lecturer:** Taka Masaki  

### **Topics Covered**  
- Introduction to Geospatial Data and Analysis  
  - What is geospatial data?  
  - Different types of geospatial data  
  - GIS file formats  
  - Examples of geospatial datasets  
  - GIS analysis software  
  - GIS analysis techniques  

### **1. Repository Structure**  

📂 **scripts/** – Contains all R replication scripts for geospatial analysis.  
📂 **figures/** – Stores all generated figures and visualizations.  
📂 **data-raw/** (external) – Store the raw datasets, which are hosted on [OneDrive](https://asiandevbank-my.sharepoint.com/:f:/g/personal/tmasaki_adb_org/EsnOzJDHHPRLqrMdMM0tlAoBALVpAxowUPD7Sdi_pkk4ig?e=26FebT).  Download and put in the `GitHub/erdi_intro_geo` folder in your local laptop.  
📂 **data-clean/** (external) – Store the clean datasets, which are hosted on [OneDrive](https://asiandevbank-my.sharepoint.com/:f:/g/personal/tmasaki_adb_org/EsnOzJDHHPRLqrMdMM0tlAoBALVpAxowUPD7Sdi_pkk4ig?e=26FebT).  Download and put in the `GitHub/erdi_intro_geo` folder in your local laptop.  

### **2. Software/Package Requirements**  
- R 4.4.2
- Open R and run:  
```r  
install.packages("pacman")
install.packages("remotes")
remotes::install_github("r-tmap/tmap")
pacman::p_load(here,dplyr,tidyverse,sf,terra,tmap,exactextractr,gdistance) 
```

### **3. Run the Replication Scripts**  
Navigate to the **scripts/** folder and execute the R scripts as needed.  

### **4. Use the Datasets**  
- Download the datasets from [OneDrive](https://asiandevbank-my.sharepoint.com/:f:/g/personal/tmasaki_adb_org/EsnOzJDHHPRLqrMdMM0tlAoBALVpAxowUPD7Sdi_pkk4ig?e=26FebT) and place them in the appropriate working directory (`GitHub/erdi_intro_geo`).  
- Ensure that file paths in the scripts match the dataset locations.  

## **Contact**  
For any questions, feel free to reach out to **Taka Masaki** at tmasaki@adb.org.  

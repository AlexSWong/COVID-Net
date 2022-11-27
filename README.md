<p align="center">
	<img src="covidnetlogo.png" alt="COVID-Net" width="30%" height="30%">
	<br>
	<img src="https://github.com/jamesrenhoulee/CancerNet-SCa/raw/main/assets/cancernet_logo.png" alt="Cancer-Net" width="13%" height="13%">
	<img src="https://github.com/darwinai/TuberculosisNet/raw/main/assets/tbnet_logo.png" alt="TB-Net" width="16%" height="16%">
	<img src="https://github.com/darwinai/FibrosisNet/raw/main/assets/fibrosisnet_logo.png" alt="TB-Net" width="16%" height="16%">	
	<br>
</p>

## COVID-Net Open Initiative (Cancer-Net, TB-Net, Fibrosis-Net Initiatives)

Launched in March 2020 in response to the coronavirus disease 2019 (COVID-19) pandemic, COVID-Net is a global open source, open access initiative dedicated to accelerating advancement in machine learning to aid front-line healthcare workers and clinical institutions around the world fighting the continuing pandemic.  Towards this goal, our global multi-disciplinary team of researchers, developers, and clinicians have made publicly available a suite of tailored deep neural network models for tackling different challenges ranging from screening to risk stratification to treatment planning for patients with the severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2).  Furthermore, we have made available fully curated, open access benchmark datasets comprised of some of the largest, most diverse patient cohorts from around the world.  We hope the open-source, open-access release of COVID-Net deep learning models and associated large-scale benchmark datasets will motivate and enable researchers, clinicians, and citizen data scientists alike from around the world to build upon them and accelerate progress in this field.  We continue to regularly release new models and benchmark datasets to keep up with the dynamic nature of the evolving pandemic, and have since expanded the initiative with the open source TB-Net initiative for tuberculosis screening, Fibrosis-Net initiative for pulmonary fibrosis progression prediction, and Cancer-Net initiative for cancer screening.

### Updates
- **November 26, 2022**: Major release of **Cancer-Net BCa**, a volumetric convolutional neural network to learn volumetric deep radiomic features for predicting the post-treatment response for breast cancer using synthetic correlated diffusion imaging, along with a new benchmark dataset of volumetric synthetic correlated diffusion imaging data from 253 patient cases [(Paper)](https://arxiv.org/abs/2211.05308)[(Models)](https://github.com/catai9/Cancer-Net-BCa)[(Datasets)](https://www.kaggle.com/datasets/amytai/cancernet-bca)
- **June 8, 2022**: Major release of **COVIDx CT-3**, a new benchmark dataset of 431,205 CT images curated through a multinational cohort of 6,068 patient cases  from at least 51 countries [(Paper)](https://arxiv.org/abs/2206.03043)[(Datasets)](https://www.kaggle.com/datasets/hgunraj/covidxct)
- **April 10, 2022**: Major release of **COVID-Net Biochem**, a collection of explainability-designed machine learning models for predicting
survival and kidney injury of COVID-19 patients from clinical and biochemistry data [(Models)](https://github.com/h-aboutalebi/CovidBiochem)[(Datasets)](https://github.com/h-aboutalebi/CovidBiochem)
- **November 28, 2021**: Major release of **COVID-Net UI**, a new AI-powered clinical decision support platform for COVID-19 [(Platform)](https://github.com/darwinai/covidnet_ui)
- **November 23, 2021**: Major release of **COVIDx CXR-3**, a new benchmark dataset of 30,882 CXR images curated through a multinational cohort of 17,036 patient cases  from at least 51 countries [(Datasets)](https://www.kaggle.com/andyczhao/covidx-cxr2)
- **October 19, 2021**: Major release of **COVID-Net CXR-3**, a tailored deep convolutional neural network for detection of COVID-19 cases from chest X-ray images using a multi-scale encoder-decoder self-attention (MEDUSA)  [(Paper)](https://arxiv.org/abs/2110.06063)[(Models)](https://github.com/lindawangg/COVID-Net/blob/master/docs/models.md)
- **August 7, 2021**: Major release of **COVID-Net US**, a tailored deep convolutional neural network for detection of COVID-19 cases from point-of-care ultrasound (POCUS) images [(Models)](https://github.com/maclean-alexander/COVID-Net-US)[(Datasets)](https://github.com/nrc-cnrc/COVID-US)
- **July 13, 2021**: Major release of **COVIDx US**, now with 29,651 processed point-of-care ultrasound (POCUS) images of patients infected with SARS-CoV-2 pneumonia, non-SARS-CoV-2 pneumonia, as well as healthy control cases. [(Paper)](https://arxiv.org/abs/2103.10003)[(Datasets)](https://github.com/nrc-cnrc/COVID-US)
- **June 10, 2021**: Major release of **Fibrosis-Net**, a tailored deep convolutional neural network for prediction of pulmonary fibrosis progression from chest CT images  [(Paper)](https://arxiv.org/abs/2103.04008)[(Models)](https://github.com/darwinai/FibrosisNet)
- **May 20, 2021**: Major release of **COVID-Net CXR-S**, a tailored deep convolutional neural network for airspace severity assessment from chest X-ray images  [(Paper)](https://arxiv.org/abs/2105.00256)[(Models)](https://github.com/lindawangg/COVID-Net/blob/master/docs/models.md)
- **May 14, 2021**: Major release of **COVIDx CXR-2**, a new benchmark dataset of CXR images curated through a multinational cohort of close to 15,000 patients from at least 51 countries [(Datasets)](https://www.kaggle.com/andyczhao/covidx-cxr2)
- **April 15, 2021**: Major release of **TB-Net**, a tailored neural network for detection of tuberculosis from chest x-ray images [(Model)](https://github.com/darwinai/TuberculosisNet) [(Paper)](https://arxiv.org/abs/2104.03165)
- **April 2, 2021**: Major release of **COVID-Net Clinical ICU**, a tailored neural network for ICU admission prediction based on patient clinical data [(Model)](https://github.com/darwinai/covidnet_clinical_ICU)
- **March 19, 2021**: Major release of **COVIDx US**, a new benchmark dataset of 10,774 processed point-of-care ultrasound (POCUS) images of patients infected with SARS-CoV-2 pneumonia, non-SARS-CoV-2 pneumonia, as well as healthy control cases.  [(Paper)](https://arxiv.org/abs/2103.10003)[(Datasets)](https://github.com/nrc-cnrc/COVID-US)
- **January 26, 2021**: Major release of **COVID-Net CT-2**, built using new benchmark dataset with CT slices from at least 15 countries [(Paper)](https://arxiv.org/pdf/2101.07433.pdf)[(Models)](https://github.com/haydengunraj/COVIDNet-CT/blob/master/docs/models.md)[(Datasets)](https://www.kaggle.com/hgunraj/covidxct)
- **January 19, 2021**: Major release of **Cancer-Net SCa**, tailored deep convolutional neural networks for detection of skin cancer from dermoscopy images [(Paper)](https://arxiv.org/abs/2011.10702)[(Models)](https://github.com/jamesrenhoulee/CancerNet-SCa/blob/main/docs/models.md)

### Benchmark Dataset Status:
- Chest x-rays: **30,882** CXR images across **17,036** patients [Click here](https://www.kaggle.com/andyczhao/covidx-cxr2)
- Chest CT: **431,205** CT slices from **6,068** patients [Click here](https://www.kaggle.com/hgunraj/covidxct)
- Chest point-of-care ultrasound: **29,651** POCUS images [Click here](https://github.com/nrc-cnrc/COVID-US)
- Clinical and biochemisty data: **1336** records [Click here](https://github.com/h-aboutalebi/CovidBiochem)
- Synthetic correlated diffusion imaging data: **253** patients [Click here](https://www.kaggle.com/datasets/amytai/cancernet-bca) 

### Resources
- <img src="covidnetlogo.png" alt="COVID-Net" width="4%" height="4%"> **COVID-Net UI: AI-Powered Clinical Decision Support Platform for COVID-19**: 
	- Repo: [Click here](https://github.com/darwinai/covidnet_ui)
  <br>
- <img src="covidnetlogo.png" alt="COVID-Net" width="4%" height="4%"> **COVID-Net CXR: tailored deep convolutional neural networks for detection of COVID-19 cases from chest X-ray images** 
  - Repo: [Click here](https://github.com/lindawangg/COVID-Net)
  - Models: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/models.md)
  - Benchmark datasets:  [Click here](https://www.kaggle.com/andyczhao/covidx-cxr2)
  - Paper: [Click here](https://www.nature.com/articles/s41598-020-76550-z)
  <br>
- <img src="covidnetlogo.png" alt="COVID-Net" width="4%" height="4%"> **COVID-Net CT: tailored deep convolutional neural networks for detection of COVID-19 cases from chest CT images**: 
  - Repo: [Click here](https://github.com/haydengunraj/COVIDNet-CT)
  - Models: [Click here](https://github.com/haydengunraj/COVIDNet-CT/blob/master/docs/models.md)
  - Benchmark datasets: [Click here](https://www.kaggle.com/hgunraj/covidxct)
  - Paper (CT-1): [Click here](https://www.frontiersin.org/articles/10.3389/fmed.2020.608525/full) 
  - Paper (CT-2): [Click here](https://arxiv.org/pdf/2101.07433.pdf)
   <br>
- <img src="covidnetlogo.png" alt="COVID-Net" width="4%" height="4%"> **COVID-Net US: tailored deep convolutional neural network for detection of COVID-19 cases from chest point-of-care ultrasound images**: 	
  - Repo: [Click here](https://github.com/maclean-alexander/COVID-Net-US)
  - Models: [Click here](https://github.com/maclean-alexander/COVID-Net-US)
  - Benchmark dataset: [Click here](https://github.com/nrc-cnrc/COVID-US)
  <br>   
- <img src="covidnetlogo.png" alt="COVID-Net" width="4%" height="4%"> **COVID-Net CXR-S: tailored deep convolutional neural networks for airspace severity assessment from chest X-ray images**: 	
  - Repo: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/covidnet_severity.md)
  - Models: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/models.md)
  - Benchmark dataset: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/covidnet_severity.md)
  - Paper: [Click here](https://arxiv.org/abs/2105.00256)
  <br>
- <img src="covidnetlogo.png" alt="COVID-Net" width="4%" height="4%"> **COVID-Net Biochem: explainability-designed machine learning models for predicting
survival and kidney injury of COVID-19 patients from clinical and biochemistry data**: 
	- Repo: [Click here](https://github.com/h-aboutalebi/CovidBiochem)
  - Model: [Click here](https://github.com/h-aboutalebi/CovidBiochem)
  - Benchmark dataset: [Click here](https://github.com/h-aboutalebi/CovidBiochem)
  <br>  
- <img src="covidnetlogo.png" alt="COVID-Net" width="4%" height="4%"> **COVID-Net Severity: tailored deep convolutional neural networks for severity assessment from chest X-ray images**: 	
	- Repo: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/models.md)
  - Models: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/models.md)
  - Benchmark dataset: [Click here](https://github.com/lindawangg/COVID-Net/tree/master/annotations)
  - Paper: [Click here](https://www.nature.com/articles/s41598-021-88538-4)
  <br>
- <img src="covidnetlogo.png" alt="COVID-Net" width="4%" height="4%"> **COVID-Net Pneumonia: tailored deep convolutional neural networks for detection of pneumonia cases from chest X-ray images**: 
	- Repo: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/covidnet_pneumonia.md)
  - Models: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/covidnet_pneumonia.md)
  - Benchmark dataset: [Click here](https://github.com/lindawangg/COVID-Net/tree/master/annotations)
  <br>
- <img src="covidnetlogo.png" alt="COVID-Net" width="4%" height="4%"> **COVIDx US: benchmark dataset for detection of COVID-19 cases from chest point-of-care ultrasound images**: 
	- Repo: [Click here](https://github.com/nrc-cnrc/COVID-US)
  - Benchmark dataset: [Click here](https://github.com/nrc-cnrc/COVID-US)
  - Paper: [Click here](https://arxiv.org/abs/2103.10003)
  <br>
- <img src="covidnetlogo.png" alt="COVID-Net" width="4%" height="4%"> **COVIDx CT-3: A Large-scale, Multinational, Open-Source Benchmark Dataset for Computer-aided COVID-19 Screening from Chest CT Images**: 
  - Benchmark dataset: [Click here](https://www.kaggle.com/datasets/hgunraj/covidxct)
  - Paper: [Click here](https://arxiv.org/abs/2206.03043)
  <br>  
- <img src="covidnetlogo.png" alt="COVID-Net" width="4%" height="4%"> **COVID-Net Clinical ICU: tailored neural network for ICU admission prediction based on patient clinical data**: 
	- Repo: [Click here](https://github.com/darwinai/covidnet_clinical_ICU)
  - Model: [Click here](https://github.com/darwinai/covidnet_clinical_ICU)
  <br>
- <img src="https://github.com/darwinai/TuberculosisNet/raw/main/assets/tbnet_logo.png" alt="COVID-Net" width="4%" height="4%"> **TB-Net: tailored deep convolutional neural networks for detection of tuberculosis cases from chest X-ray images**: 
	- Repo: [Click here](https://github.com/darwinai/TuberculosisNet)
  - Model: [Click here](https://github.com/darwinai/TuberculosisNet/blob/main/docs/models.md)
  - Paper: [Click here](https://arxiv.org/abs/2104.03165)
  <br>    
- <img src="https://github.com/darwinai/FibrosisNet/raw/main/assets/fibrosisnet_logo.png" alt="COVID-Net" width="4%" height="4%"> **Fibrosis-Net: tailored deep convolutional neural networks for prediction of pulmonary fibrosis progression from chest CT images**: 
	- Repo: [Click here](https://github.com/darwinai/FibrosisNet)
  - Model: [Click here](https://github.com/darwinai/FibrosisNet)
  - Paper: [Click here](https://arxiv.org/abs/2103.04008)
  <br>      
- <img src="https://github.com/jamesrenhoulee/CancerNet-SCa/raw/main/assets/cancernet_logo.png" alt="COVID-Net" width="4%" height="4%"> **Cancer-Net SCa: tailored deep convolutional neural networks for detection of skin cancer from dermoscopy images**: 
	- Repo: [Click here](https://github.com/jamesrenhoulee/CancerNet-SCa)
  - Models: [Click here](https://github.com/jamesrenhoulee/CancerNet-SCa/blob/main/docs/models.md)
  - Paper: [Click here](https://arxiv.org/abs/2011.10702)
  <br>
- <img src="https://github.com/jamesrenhoulee/CancerNet-SCa/raw/main/assets/cancernet_logo.png" alt="COVID-Net" width="4%" height="4%"> **Cancer-Net BCa: Breast Cancer Pathologic Complete Response Prediction using Volumetric Deep Radiomic Features from Synthetic Correlated Diffusion Imaging**: 
	- Repo: [Click here](https://github.com/catai9/Cancer-Net-BCa)
  - Models: [Click here](https://github.com/catai9/Cancer-Net-BCa)
  - Dataset: [Click here](https://www.kaggle.com/datasets/amytai/cancernet-bca)  
  - Paper: [Click here](https://arxiv.org/abs/2211.053082)  
  <br>

## Core COVID-Net Team

Project Lead: [Alexander Wong](http://www.eng.uwaterloo.ca/~a28wong) (a28wong@uwaterloo.ca)

* DarwinAI Corp., Canada and Vision and Image Processing Research Group, University of Waterloo, Canada
  * Linda Wang
  * Alexander Wong
  * Zhong Qiu Lin
  * Paul McInnis
  * Audrey Chung
  * Melissa Rinch
  * Maya Pavlova
  * Hadi Rahmat-Khah
  * Naomi Terhljan
  * Hadi Rahmat-Khah
  * Siddharth Surana
  * Hayden Gunraj
  * Jeffer Peng
  * James Lee 
* Vision and Image Processing Research Group, University of Waterloo, Canada
  * Hossein Aboutalebi
  * Amy Tai
  * Alex MacLean
  * Saad Abbasi
  * Andy Zhao
  * Frank Shi
  * Yuetong Wang  
* Ashkan Ebadi and Pengcheng Xi (National Research Council Canada)
* Ali Sabri (Niagara Health, McMaster University, Canada)
* Adrian Florea (St. Mary's Hospital, McGill University, Canada)
* Amer Alaref (Thunder Bay Regional Health Sciences Centre, Northern Ontario School of Medicine, Canada)
* Kim-Ann Git (Selayang Hospital)
* Abdul Al-Haimi

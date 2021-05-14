<p align="center">
	<img src="covidnetlogo.png" alt="COVID-Net" width="30%" height="30%">
	<br>
	<img src="https://github.com/jamesrenhoulee/CancerNet-SCa/raw/main/assets/cancernet_logo.png" alt="Cancer-Net" width="13%" height="13%">
	<img src="https://github.com/darwinai/TuberculosisNet/raw/main/assets/tbnet_logo.png" alt="TB-Net" width="16%" height="16%">
	<br>
</p>

## COVID-Net Open Initiative

Launched in March 2020 in response to the coronavirus disease 2019 (COVID-19) pandemic, COVID-Net is a global open source, open access initiative dedicated to accelerating advancement in machine learning to aid front-line healthcare workers and clinical institutions around the world fighting the continuing pandemic.  Towards this goal, our global multi-disciplinary team of researchers, developers, and clinicians have made publicly available a suite of tailored deep neural network models for tackling different challenges ranging from screening to risk stratification to treatment planning for patients with the severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2).  Furthermore, we have made available fully curated, open access benchmark datasets comprised of some of the largest, most diverse patient cohorts from around the world.  We hope the open-source, open-access release of COVID-Net deep learning models and associated large-scale benchmark datasets will motivate and enable researchers, clinicians, and citizen data scientists alike from around the world to build upon them and accelerate progress in this field.  We continue to regularly release new models and benchmark datasets to keep up with the dynamic nature of the evolving pandemic, and have since expanded the initiative with the open source TB-Net initiative for tuberculosis screening and Cancer-Net initiative for cancer screening.

### Updates
- **May 14, 2021**: Major release of **COVIDx CXR-2**, a new benchmark dataset of CXR images curated through a multinational cohort of close to 15,000 patients from at least 51 countries [(Datasets)](https://www.kaggle.com/andyczhao/covidx-cxr2)
- **April 15, 2021**: Major release of **TB-Net**, a tailored neural network for detection of tuberculosis from chest x-ray images [(Model)](https://github.com/darwinai/TuberculosisNet) [(Paper)](https://arxiv.org/abs/2104.03165)
- **April 2, 2021**: Major release of **COVID-Net Clinical ICU**, a tailored neural network for ICU admission prediction based on patient clinical data [(Model)](https://github.com/darwinai/covidnet_clinical_ICU)
- **March 19, 2021**: Major release of **COVIDx US**, a new benchmark dataset of 10,774 processed point-of-care ultrasound (POCUS) images of patients infected with SARS-CoV-2 pneumonia, non-SARS-CoV-2 pneumonia, as well as healthy control cases. [(Paper)](https://arxiv.org/abs/2103.10003)[(Datasets)](https://github.com/nrc-cnrc/COVID-US)
- **January 26, 2021**: Major release of **COVID-Net CT-2**, built using new benchmark dataset with CT slices from at least 15 countries [(Paper)](https://arxiv.org/pdf/2101.07433.pdf)[(Models)](https://github.com/haydengunraj/COVIDNet-CT/blob/master/docs/models.md)[(Datasets)](https://www.kaggle.com/hgunraj/covidxct)
- **January 19, 2021**: Major release of **Cancer-Net SCa**, tailored deep convolutional neural networks for detection of skin cancer from dermoscopy images [(Paper)](https://arxiv.org/abs/2011.10702)[(Models)](https://github.com/jamesrenhoulee/CancerNet-SCa/blob/main/docs/models.md)

### Benchmark Dataset Status:
- Chest x-rays: **16,352** CXR images across **14,979** patients [Click here](https://www.kaggle.com/andyczhao/covidx-cxr2)
- Chest CT: **201,103** CT slices from **4,501** patients [Click here](https://www.kaggle.com/hgunraj/covidxct)
- Chest point-of-care ultrasound: **12,943** POCUS images [Click here](https://github.com/nrc-cnrc/COVID-US)

### Resources
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
- <img src="covidnetlogo.png" alt="COVID-Net" width="4%" height="4%"> **COVID-Net CXR-S: tailored deep convolutional neural networks for airspace severity assessment from chest X-ray images**: 	
  - Repo: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/covidnet_severity.md)
  - Models: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/models.md)
  - Benchmark dataset: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/covidnet_severity.md)
  - Paper: [Click here](https://arxiv.org/abs/2105.00256)
  <br>
- <img src="covidnetlogo.png" alt="COVID-Net" width="4%" height="4%"> **COVID-Net Severity: tailored deep convolutional neural networks for severity assessment from chest X-ray images**: 	
	- Repo: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/models.md)
  - Models: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/models.md)
  - Benchmark dataset: [Click here](https://github.com/lindawangg/COVID-Net/tree/master/annotations)
  - Paper: [Click here](https://arxiv.org/abs/2005.12855)
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
- <img src="covidnetlogo.png" alt="COVID-Net" width="4%" height="4%"> **COVID-Net Clinical ICU: tailored neural network for ICU admission prediction based on patient clinical data**: 
	- Repo: [Click here](https://github.com/darwinai/covidnet_clinical_ICU)
  - Model: [Click here](https://github.com/darwinai/covidnet_clinical_ICU)
  <br>
- <img src="https://github.com/darwinai/TuberculosisNet/raw/main/assets/tbnet_logo.png" alt="COVID-Net" width="4%" height="4%"> **TB-Net: tailored deep convolutional neural networks for detection of tuberculosis cases from chest X-ray images**: 
	- Repo: [Click here](https://github.com/darwinai/TuberculosisNet)
  - Model: [Click here](https://github.com/darwinai/TuberculosisNet/blob/main/docs/models.md)
  - Paper: [Click here](https://arxiv.org/abs/2104.03165)
  <br>    
- <img src="https://github.com/jamesrenhoulee/CancerNet-SCa/raw/main/assets/cancernet_logo.png" alt="COVID-Net" width="4%" height="4%"> **Cancer-Net SCa: tailored deep convolutional neural networks for detection of skin cancer from dermoscopy images**: 
	- Repo: [Click here](https://github.com/jamesrenhoulee/CancerNet-SCa)
  - Models: [Click here](https://github.com/jamesrenhoulee/CancerNet-SCa/blob/main/docs/models.md)
  - Paper: [Click here](https://arxiv.org/abs/2011.10702)
  <br>
- <img src="covidnetlogo.png" alt="COVID-Net" width="4%" height="4%"> **COVID-Net GUI: graphic user interface front-end for COVID-Net models**: 
	- Repo: [Click here](https://github.com/darwinai/covidnet_ui)
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
  * Naomi Terhljan
  * Siddharth Surana
  * Hayden Gunraj
  * Jeffer Peng
  * James Lee 
* Vision and Image Processing Research Group, University of Waterloo, Canada
  * Hossein Aboutalebi
  * Alex MacLean
  * Saad Abbasi
  * Andy Zhao
* Ashkan Ebadi and Pengcheng Xi (National Research Council Canada)
* Ali Sabri (Niagara Health, McMaster University, Canada)
* Amer Alaref (Thunder Bay Regional Health Sciences Centre, Northern Ontario School of Medicine, Canada)
* Kim-Ann Git (Selayang Hospital)
* Abdul Al-Haimi

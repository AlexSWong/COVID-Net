<p align="center">
	<img src="covidnetlogo.png" alt="COVID-Net" width="30%" height="30%">
	<br>
</p>

## COVID-Net Open Initiative

Launched in March 2020 in response to the coronavirus disease 2019 (COVID-19) pandemic, COVID-Net is a global open source, open access initiative dedicated to accelerating advancement in machine learning to aid front-line healthcare workers and clinical institutions around the world fighting the continuing pandemic.  Towards this goal, our global multi-disciplinary team of researchers, developers, and clinicians have made publicly available a suite of tailored deep neural network models for tackling different challenges ranging from screening to risk stratification to treatment planning for patients with the severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2).  Furthermore, we have made available fully curated, open access benchmark datasets comprised of some of the largest, most diverse patient cohorts from around the world.  We hope the open-source, open-access release of COVID-Net deep learning models and associated large-scale benchmark datasets will motivate and enable researchers, clinicians, and citizen data scientists alike from around the world to build upon them and accelerate progress in this field.  We continue to regularly release new models and benchmark datasets to keep up with the dynamic nature of the evolving pandemic, and have since expanded the initiative with the open source Cancer-Net initiative.

### Updates
- **March 19, 2021**: Major release of **COVIDx US**, a new benchmark dataset of 10,774 processed point-of-care ultrasound (POCUS) images of patients infected with SARS-CoV-2 pneumonia, non-SARS-CoV-2 pneumonia, as well as healthy control cases. [(Datasets)](https://github.com/nrc-cnrc/COVID-US)
- **January 26, 2021**: Major release of **COVID-Net CT-2**, built using new benchmark dataset with CT slices from at least 15 countries [(Paper)](https://arxiv.org/pdf/2101.07433.pdf)[(Models)](https://github.com/haydengunraj/COVIDNet-CT/blob/master/docs/models.md)[(Datasets)](https://www.kaggle.com/hgunraj/covidxct)
- **January 19, 2021**: Major release of **Cancer-Net SCa**, tailored deep convolutional neural networks for detection of skin cancer from dermoscopy images [(Paper)](https://arxiv.org/abs/2011.10702)[(Models)](https://github.com/jamesrenhoulee/CancerNet-SCa/blob/main/docs/models.md)

### Benchmark Dataset Status:
- Chest x-rays: **15,664** CXR images across **15,351** patients [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/COVIDx.md)
- Chest CT: **201,103** CT slices from **4,501** patients [Click here](https://www.kaggle.com/hgunraj/covidxct)
- Chest point-of-care ultrasound: **10,774** POCUS images [Click here](https://github.com/nrc-cnrc/COVID-US)
- 
### COVID-Net Resources
- **COVID-Net CXR: tailored deep convolutional neural networks for detection of COVID-19 cases from chest X-ray images** 
	- Repo: [Click here](https://github.com/lindawangg/COVID-Net)
  - Models: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/models.md)
  - Benchmark datasets:  [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/COVIDx.md)
  - Paper: [Click here](https://www.nature.com/articles/s41598-020-76550-z)
  <br>
  
- **COVID-Net CT: tailored deep convolutional neural networks for detection of COVID-19 cases from chest CT images**: 
	- Repo: [Click here](https://github.com/haydengunraj/COVIDNet-CT)
  - Models: [Click here](https://github.com/haydengunraj/COVIDNet-CT/blob/master/docs/models.md)
  - Benchmark datasets: [Click here](https://www.kaggle.com/hgunraj/covidxct)
  - Paper (CT-1): [Click here](https://www.frontiersin.org/articles/10.3389/fmed.2020.608525/full) 
  - Paper (CT-2): [Click here](https://arxiv.org/pdf/2101.07433.pdf)
   <br>
 
- **COVID-Net Severity: tailored deep convolutional neural networks for severity assessment from chest X-ray images**: 	
	- Repo: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/models.md)
  - Models: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/models.md)
  - Benchmark dataset: [Click here](https://github.com/lindawangg/COVID-Net/tree/master/annotations)
  - Paper: [Click here](https://arxiv.org/abs/2005.12855)
  <br>
- **COVID-Net Pneumonia: tailored deep convolutional neural networks for detection of pneumonia cases from chest X-ray images**: 
	- Repo: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/covidnet_pneumonia.md)
  - Models: [Click here](https://github.com/lindawangg/COVID-Net/blob/master/docs/covidnet_pneumonia.md)
  - Benchmark dataset: [Click here](https://github.com/lindawangg/COVID-Net/tree/master/annotations)
  <br>
- **COVIDx US: benchmark dataset for detection of COVID-19 cases from chest point-of-care ultrasound images**: 
	- Repo: [Click here](https://github.com/nrc-cnrc/COVID-US)
  - Benchmark dataset: [Click here](https://github.com/nrc-cnrc/COVID-US)
  <br>
  
- **Cancer-Net SCa: tailored deep convolutional neural networks for detection of skin cancer from dermoscopy images**: 
	- Repo: [Click here](https://github.com/jamesrenhoulee/CancerNet-SCa)
  - Models: [Click here](https://github.com/jamesrenhoulee/CancerNet-SCa/blob/main/docs/models.md)
  - Paper: [Click here](https://arxiv.org/abs/2011.10702)
  <br>
- **COVID-Net GUI: graphic user interface front-end for COVID-Net models**: 
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
* Ashkan Ebadi and Pengcheng Xi (National Research Council Canada)
* Ali Sabri (Niagara Health, McMaster University, Canada)
* Kim-Ann Git (Selayang Hospital)
* Abdul Al-Haimi

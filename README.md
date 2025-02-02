# A Systematic Survey of Public Computer Vision Dataset for Precision Livestock Farming 
## How to Contribute?
We are trying to build a large dataset for PLF like in other application domain. Please share your link if you have dataset. Also, if you found any missed papers, feel free to send it to us or submit [Pull Reuests](https://github.com/Anil-Bhujel/Public-Computer-Vision-Dataset-A-Systematic-Survey/branches):

1. Use following markdown format.
+
         *Author 1, Author 2, and Author 3.* **Paper Title.**  <ins>Conference/Journal/Preprint</ins> Year. [[pdf](link)]; [[other resources](link)].
2. If one preprint paper has multiple versions, please use the earliest submitted year.
3. Display the papers in descending order as per publication date (the latest, the first).

## Citation
        Bhujel, A., Wang, Y., Lu, Y., Morris, D., Dangol, M. A systematic survey of public computer vision datasets for precision livestock farming.
Computers and Electronics in Agriculture, (229) 2025, 109718. https://doi.org/10.1016/j.compag.2024.109718.


## 🔍 Table of Contents
### [1. Introduction](#1-introduction)
### [2. Methodology](#2-methodology)
### [3. Datasets](#3-datasets)
-  3.1 Cattle Datasets
-  3.2 Swine Datasets
-  3.3 Poultry Datasets
-  3.4 Other Livestock Datasets
### [4. Discussion](#4-discussion)
-  4.1 Application-wise Datasets
-  4.2 Modality of Image Datasets
-  4.3 Challenges and Prospects in CV Dataset Preparation
### [5. Conclusion](#5-conclusion)

## 1. Introduction
The existing surveys related to the computer vision in livestock are insufficient regarding in-depth coverage, classification, and comparison of each dataset and its application in PLF. The main contribution of this survey is to identify, classify, and comprehensive discussion of public livestock datasets. Moreover, the data acquisition techniques, application scenarios, and baseline evaluations of the selected datasets are highlighted.
## 2. Methodology
The survey methodology:
-	Setting the study scope
-	Identifying the inclusion criteria
-	Selecting the journal paper 
-	Systematic reviewing of the selected articles.
-	Finding the knowledge gap or future perspectives

Criterias of a paper to be selected for detailed study
-	The data should be used for computer vision application. 
-	The data should be publicly available without requiring the author’s consent. 
-	The data should be used in any livestock phenotype study.
-	The research paper published since 2015 is contemplated in this study

## 3. Datasets
This section presents the comprehensive study of available public computer vision datasets related to livestock.
### 3.1 Cattle Datasets
#### 3.1.1 Cattle Detection Datasets
-  [FriesianCattle2017](https://data.bris.ac.uk/data/dataset/2yizcfbkuv4352pzc32n54371r) (Andrew et al., 2017)
-  [AerialCattle2017](https://data.bris.ac.uk/data/dataset/3owflku95bxsx24643cybxu3qh) (Andrew et al. 2017)
-  [Aerial-livestock-dataset](https://github.com/hanl2010/Aerial-livestock-dataset/releases) (Han et al., 2019)
-  [OpenCows2020](https://data.bris.ac.uk/data/dataset/10m32xl88x2b61zlkkgz3fml17)(Andrew et al., 2021)
-  [Cows2021](https://data.bris.ac.uk/data/dataset/4vnrca7qw1642qlwxjadp87h7) (Gao et al., 2021)
-  [MultiviewC](https://github.com/Jiahao-Ma/MultiviewC) (Ma et al., 2021)
-  [Cattle-counting](https://vhasoares.github.io/downloads.html) (Soares et al., 2021)
-  [Aerial Pasture](http://bird.nae-lab.org/cattle/) (Shao et al., 2020)
-  [Cattle_Video_Behaviors (CVB)](https://data.csiro.au/collection/csiro%3A58916v1) (Zia et al., 2023)
-  [Cows Frontal Face](https://zenodo.org/records/10535934) (Ahmed et al., 2024)

#### 3.1.2 Cattle Classification Datasets
-  [FriesianCattle2015](https://data.bris.ac.uk/data/dataset/wurzq71kfm561ljahbwjhx9n3) (Andrew et al., 2016)
-  [BeefCattleMuzzle](http://doi.10.5281/zenodo.6324360) (G. Li et al., 2022)
-  [Holstein CowRecognition](https://dataverse.nl/dataset.xhtml?persistentId=doi:10.34894/O1ZBSA) (Bhole et al., 2019)
-  [HolsteinCattle](https://dataverse.nl/dataset.xhtml?persistentId=doi:10.34894/7M108F) (Bhole et al., 2022)
-  [RecBov51c Dataset](https://data.mendeley.com/datasets/8ysxtyf8p2/1) (Weber et al., 2020)
-  [CowBehavior](https://zenodo.org/record/3981400#.ZDVEXHZBxPY) (Koskela et al., 2022)
-  [300-Cattle-Source](https://cloud.une.edu.au/index.php/s/eMwaHAPK08dCDru) (Shojaeipour et al., 2021)
-  [CattleVideo](https://drive.google.com/file/d/13LZmzb5XcqzUVQo3EiTIf4pur4lFHmZD/view?usp=sharing) (Qiao et al., 2021a)
-  [CVD Cattle Retinal Image](https://www.kaggle.com/datasets/animalbiometry/cvd-vs-non-cvd-retinal-images-of-cattle) (Cihan et al., 2024)
-  [Cattle_Dataset](https://github.com/Oliver6999/cattle_dataset/tree/main) (Z. Li et al., 2022)

#### 3.1.3 Cattle Other Datasets
-  [BCS Cattle Dataset](https://datadryad.org/stash/dataset/doi:10.5061/dryad.tqjq2bw4s) (Winkler et al., 2024)
-  [NWAFU_CattleDataset](https://drive.google.com/open?id=1bLQFHd9rqllmEaYvbcAqEBJtlyfuKPdP) (Li et al., 2019)
-  [CowDB](https://github.com/ruchaya/CowDB) (Ruchay et al., 2020)
-  [CowDatabase](https://github.com/ruchaya/CowDatabase) (Ruchay et al., 2020)
-  [CowDatabase2](https://github.com/ruchaya/CowDatabase2) (Ruchay et al., 2022b)
-  [LShapeAnalyser-cow](https://gitee.com/kznd/lshape-analyser/tree/master/Dataset/dairy) (Zhang et al., 2023)
-  [PCD Dataset](https://github.com/colorful-days/0724/tree/master/data) (Hou et al., 2023)
-  [CattleEyeView](https://github.com/AnimalEyeQ/CattleEyeView?tab=readme-ov-file) (Ong et al., 2023)
-  [Dairy Cow](https://www.kaggle.com/twisdu/dairycow) (Gong et al., 2022)
-  [ADE Cattle Dataset](https://github.com/wuyiqii/Accelerated-Data-Engine) (Wu et al., 2024)
-  [CattNIS dataset](https://www.kaggle.com/datasets/animalbiometry/cattle-retinal-fundus-images) (Saygılı et al., 2024)
-  [Cattle Side&BackView Dataset](https://data.mendeley.com/datasets/h2s22wr5py/2) (Bai et al., 2024)


### 3.2 Swine Datasets
#### 3.2.1 Swine Detection Datasets
-  [PigBehavior](https://data.ncl.ac.uk/articles/dataset/Automated_recognition_of_postures_and_drinking_behaviour_for_the_detection_of_compromised_health_in_pigs/13042619)(Alameer et al., 2020a)
-  [PigPosture](https://wi2.uni-hohenheim.de/fileadmin/einrichtungen/wi2/Publikationen/COMPAG_105391_Riekert_etal_2020.zip) (Riekert et al., 2020)
-  [Pig_Detection](https://github.com/majrie/pig_detection_dataset/raw/main/COMPAG_106213_Riekert_et_al_2021.zip) (Riekert et al., 2021)
-  [Pig_Behaviors](https://drive.google.com/drive/folders/1C_wABDzfpdaRykVHoWSN8vAaLXs8Yaxn.) (Bergamini et al., 2021)
-  [Multi-camera-pig-tracking](https://drive.google.com/drive/folders/1E2wW2aRENgy_TqlzfICn58ahbTHVIaK6) (Shirke et al., 2021b)
-  [PigPostureAcitvity](https://drive.google.com/file/d/1DmkR5AyysQkFbMEwjPjJnnNVyGvtsu9H/view) (Bhujel et al., 2021)
-  [ORP-PigTracking](https://doi.org/10.6084/m9.figshare.24303259) (Lu et al., 2024)

#### 3.2.2 Swine Classification Datasets
-  [PNPB dataset](https://drive.google.com/drive/folders/14XUYxM15NAI-zBrntrmQofhLv5otAw5b) (Shirke et al., 2021a)
-  [PigFeeding-NNVBehavior](https://data.ncl.ac.uk/articles/dataset/Automatic_recognition_of_feeding_and_foraging_behaviour_in_pigs_using_deep_learning/13084148) (Alameer et al., 2020b)
-  [PigAgonistcBehavior](https://osf.io/wa732/) (Han et al., 2023)
-  [CountingPigs](https://github.com/xixiareone/counting-pigs) (Tian et al., 2019)
-  [DifferentStagesPig](https://data.mendeley.com/datasets/vd5vmgr8kghttps://data.mendeley.com/datasets/jy6hngx7df) (Pan et al., 2023)
-  [Aggressive-Behavior-Recognition](https://github.com/IPCLab-NEAU/Aggressive-Behavior-Recognition) (Gao et al., 2023)

#### 3.2.3 Swine Other Datasets
-  [Pig-multi-part-detection](http://psrg.unl.edu/Projects/Details/12-Animal-Tracking) (Psota et al., 2019) (*The author confirmed that the link of this dataset has been down now. If you need this dataset please contact to author or us.)
-  [Pig_tracking](http://psrg.unl.edu/Projects/Details/12-Animal-Tracking) (Psota et al., 2020) (*The author confirmed that the link of this dataset has been down now. If you need this dataset please contact to author or us.)
-  [Pig-detection&tracking](https://github.com/MartinWut/Supp_DetAnIn) (Wutke et al., 2021)
-  [PigTrace](https://drive.google.com/file/d/1s-bCnABh2Hef5l5OxydcY-tkPbrUGSjj/view) (Tangirala et al., 2021)
-  [LShapeAnalyser Dataset](https://gitee.com/kznd/lshape-analyser/tree/master/Dataset/pig) (Zhang et al., 2023)
-  [PigLife Dataset](https://data.aifarms.org/view/piglife) ((Li et al., 2024)

### 3.3 Poultry Datasets
-  [ChickenGender](https://drive.google.com/drive/folders/1eGq8dWGL0I3rW2B9eJ_casH0_D3x7R73) (Yao et al., 2020)
-  [Chicken_Poo](https://data.mendeley.com/datasets/8pnbzpt2k9/1) (Aworinde et al., 2023)
-  [Poultry_Disease](https://zenodo.org/record/4628934#.YtDNzOxBy1u) (Machuve et al., 2022)
-  [GalliformeSpectra](https://data.mendeley.com/datasets/nk3zbvd5h8/1) (Himel GMS and Islam MM, 2023)
-  [Broiler Dataset](https://drive.google.com/drive/folders/1jj9LKL0d1YDyDez8xrmKWRWd3psFoeZ2?usp=sharing) (Elmessery et al., 2023)
-  [BCLayingHens](https://github.com/maweihong/BClayinghens.git) (Ma et al., 2024b)
### 3.4 Other Livestock Datasets
-  [SheepBreed](https://data.mendeley.com/datasets/64gkbz8bdb/2) (Abu Jwade et al., 2019)
-  [SheepBase](https://pan.baidu.com/s/1HgNdEYqAz2SXpEbrmEb8UA) (extraction code: zrcp) (Xue et al., 2021)
-  SheepActivity Dataset [Link1](https://data.mendeley.com/datasets/w65pvb84dg/1) and [Link2](https://data.mendeley.com/datasets/h5ppwx6fn4/1) (Kelly et al., 2024) 
-  [LEsheepWeight](https://pan.baidu.com/s/1lkF50WdG6vWCnj1TAw_LjA) (code: 9hks) (He et al., 2023)
-  DORIS Dataset [Sheep:](https://zenodo.org/records/11313800), [Person, Wolf, and Depth Maps:](https://zenodo.org/records/11313966), and [YOLO Annotations:](https://zenodo.org/records/11313165) (Yang et al., 2024)
-  [GoatImage](https://data.mendeley.com/datasets/4skwhnrscr/2) (Billah et al., 2022)
-  [Drone-goat-detection](https://gitlab.com/inra-urz/drone-goat-detection) (Vayssade et al., 2019)
-  [CherryChevre](https://doi.org/10.57745/QEZBNA) (Vayssade et al., 2023)
-  [Buffalo-Pak](https://data.mendeley.com/datasets/vdgnxsm692/2) (Rauf, HT and Lali, MIU, 2021)
-  [Horse-10](http://www.mackenziemathislab.org/horse10) (Mathis et al., 2019)
## 4. Discussion
This section presents the critical analysis of public computer vision livestock dataset in terms of species, applications, and image modalities.
### 4.1 Application-wise Datasets
![Figure 7](https://github.com/user-attachments/assets/0c5ba1bb-3d03-49e0-b452-7a67da687ced)

### 4.2 Modality of Image Datasets
![Figure 8](https://github.com/user-attachments/assets/1a62f7ee-32f9-4d79-83ec-4634812631f2)


### 4.3 Challenges and Prospects in Public CV Livestock Datasets
Limitations:
-  Limited or no metadata to provide the contextual information of the data
-  No uniformity in data collection and annotation due to lack of well-accepted protocols and standards for livestock farming
-  .................

Prospects:
-  A collective effort from diverse stakeholders (academia, industry, researchers, and funding agencies) could publish standards and protocols related to data collection and preparation
-  A leading role from the accredited organizations is inevitable in building a large benchmarking database for PLF
-  ......................
  
## 5. Conclusion

# <p align=center>`Awesome Remote Sensing Spatiotemporal Fusion Models`</p>
<p align="center">
  <a href="https://github.com/ArboriseRS/Awesome-Spatiotemporal-Fusion-Models/graphs/commit-activity">
    <img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" alt="Maintenance">
  </a>
  <a href="https://github.com/ArboriseRS/Awesome-Spatiotemporal-Fusion-Models">
    <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome">
  </a>
  <a href="https://github.com/ArboriseRS/Awesome-Spatiotemporal-Fusion-Models/watchers">
    <img src="https://img.shields.io/github/watchers/ArboriseRS/Awesome-Spatiotemporal-Fusion-Models?style=social" alt="Watchers">
  </a>
  <a href="https://github.com/ArboriseRS/Awesome-Spatiotemporal-Fusion-Models/stargazers">
    <img src="https://img.shields.io/github/stars/ArboriseRS/Awesome-Spatiotemporal-Fusion-Models?style=social" alt="Stars">
  </a>
  <a href="https://github.com/ArboriseRS/Awesome-Spatiotemporal-Fusion-Models/network/members">
    <img src="https://img.shields.io/github/forks/ArboriseRS/Awesome-Spatiotemporal-Fusion-Models?style=social" alt="Forks">
  </a>
</p>

**📚 A collection of papers, datasets, and code implementations for remote sensing spatiotemporal fusion models.**

---

## 📢 Latest Updates

🔥🔥🔥 Last Updated on 2025.08.03 🔥🔥🔥

---

## 📁 Table of Contents

* [📊 Traditional Methods](#-traditional-methods)
* [🧠 CNN-Based Models](#-cnn-based-models)
* [🔍 Transformer-Based Models](#-transformer-based-models)
* [🎨 GAN-Based Models](#-gan-based-models)
* [🔀 Other Models](#-other-models)
* [🎯 Datasets & Benchmarks](#-datasets--benchmarks)

---

## 📊 Traditional Methods
Weighted reconstruction-based （WR-based） methods、Unmixing-based methods、Dictionary learning-based methods、Hybrid methods.


|   Abbreviation   | Paper                                                                                                                                                                                                                                                 | Year |                  Method                  |                                         Code                                          |
| :--------------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--: | :--------------------------------------: | :-----------------------------------------------------------------------------------: |
|      STARFM      | [On the Blending of the Landsat and MODIS Surface Reflectance: Predicting Daily Landsat Surface Reflectance](https://ieeexplore.ieee.org/document/1661809)                                                                                            | 2006 |         Weighted reconstruction          |                     [Link](https://github.com/nmileva/starfm4py)                      |
|     ESTARFM      | [An enhanced spatial and temporal adaptive reflectance fusion model for complex heterogeneous regions](https://www.sciencedirect.com/science/article/abs/pii/S0034425710001884?via%3Dihub#preview-section-snippets)                                   | 2010 |         Weighted reconstruction          |            [Link](https://xzhu-lab.github.io/Pride/Open-Source-Code.html)             |
|      SPSTFM      | [Spatiotemporal reflectance fusion via sparse representation](https://ieeexplore.ieee.org/document/6169983)                                                                                                                                           | 2012 |           Dictionary learning            |                                    [Link](SPSTFM)                                     |
|       SSIF       | [Spatiotemporal Satellite Image Fusion Through One-Pair Image Learning](https://ieeexplore.ieee.org/abstract/document/6329421)                                                                                                                        | 2013 |           Dictionary learning            |                                     [Link](SSIF)                                      |
|      FSDAF       | [A flexible spatiotemporal method for fusing satellite images with different resolutions](https://www.sciencedirect.com/science/article/abs/pii/S0034425715302042?via%3Dihub)                                                                         | 2016 |                  Hybrid                  |            [Link](https://xzhu-lab.github.io/Pride/Open-Source-Code.html)             |
|      Fit-FC      | [Spatio-temporal fusion for daily Sentinel-2 images](https://www.sciencedirect.com/science/article/abs/pii/S0034425717305096?via%3Dihub)                                                                                                              | 2018 |         Weighted reconstruction          |                     [Link](https://github.com/qunmingwang/Fit-FC)                     |
|      IFSDAF      | [An Improved Flexible Spatiotemporal DAta Fusion (IFSDAF) method for producing high spatiotemporal resolution normalized difference vegetation index time series](https://www.sciencedirect.com/science/article/abs/pii/S0034425719301038?via%3Dihub) | 2019 |                 Unmixing                 |                     [Link](https://github.com/wangwei1208/IFSDAF)                     |
| modified-ESTARFM | [An enhanced spatiotemporal fusion method – Implications for coal fire monitoring using satellite imagery](https://www.sciencedirect.com/science/article/pii/S0303243419309237?via%3Dihub)                                                            | 2020 |         Weighted reconstruction          | [Link](https://github.com/raktim-ghosh/Spatiotemporal-Data-Fusion?tab=readme-ov-file) |
|       VSDF       | [VSDF: A variation-based spatiotemporal data fusion method](https://www.sciencedirect.com/science/article/pii/S0034425722004151?via%3Dihub)                                                                                                           | 2022 |                  Hybrid                  |                      [Link](https://github.com/ChenXuAxel/VSDF)                       |
|      OBSTFM      | [A Flexible Object-Level Processing Strategy to Enhance the Weight Function-Based Spatiotemporal Fusion Method](https://ieeexplore.ieee.org/document/9912409)                                                                                         | 2022 |               Object-Level               |  [Link](https://github.com/Andy-cumt/Object-level-spatiotemporal-fusion-models)<br>   |
|      RASDF       | [A reliable and adaptive spatiotemporal data fusion method for blending multi-spatiotemporal-resolution satellite images](https://www.sciencedirect.com/science/article/abs/pii/S0034425721004909?via%3Dihub)                                         | 2022 |                 Unmixing                 |                    [Link](https://github.com/Andy-cumt/RASDF_GUI)                     |
|      CFSDAF      | [A Comprehensive Flexible Spatiotemporal DAta Fusion Method (CFSDAF) for Generating High Spatiotemporal Resolution Land Surface Temperature in Urban Area](https://ieeexplore.ieee.org/document/9946977)                                              | 2022 |                  Hybrid                  |                   [Link](https://github.com/ChenlieShi-NWU/CFSDAF)                    |
|    Agri-Fuse     | [Agri-Fuse: A novel spatiotemporal fusion method designed for agricultural scenarios with diverse phenological changes](https://www.sciencedirect.com/science/article/abs/pii/S003442572300425X?via%3Dihub)                                           | 2023 |                 Unmixing                 |                    [Link](https://github.com/GuZhuoning/Agri-Fuse)                    |
|      ROBOT       | [ROBOT: A spatiotemporal fusion model toward seamless data cube for global remote sensing applications](https://www.sciencedirect.com/science/article/abs/pii/S0034425723001670?via%3Dihub)                                                           | 2023 | Hybrid(LASSO and distributing residuals) |                     [Link](https://github.com/shuangchencc/ROBOT)                     |
|      OBSUM       | [OBSUM: An object-based spatial unmixing model for spatiotemporal fusion of remote sensing images](https://www.sciencedirect.com/science/article/pii/S0034425724000579?via%3Dihub)                                                                    | 2024 |                 Unmixing                 |                    [Link](https://github.com/HoucaiGuo/OBSUM-code)                    |
|     FastVSDF     | [FastVSDF: An Efficient Spatiotemporal Data Fusion Method for Seamless Data Cube](https://ieeexplore.ieee.org/document/10399795)                                                                                                                      | 2024 |                  Hybrid                  |                 [Link](https://ieeexplore.ieee.org/document/10399795)                 |
| SST-Data-Fusion  | [High Spatiotemporal Resolution Sea Surface  Temperature From MERSI and AGRI Sensors  Based on Spatial and Temporal Adaptive Sea  Surface Temperature Fusion Model](https://ieeexplore.ieee.org/document/10637434)                                    | 2024 |               Hybrid(SST)                |                   [Link](https://github.com/zhgis/SST-Data-Fusion)                    |
|     GLOSTFM      | [GLOSTFM: A global spatiotemporal fusion model integrating multi-source satellite observations to enhance land surface temperature resolution](https://www.sciencedirect.com/science/article/abs/pii/S0034425725000446?via%3Dihub)                    | 2025 |         Image Pyramid Principles         |           [Link](https://github.com/1426922668/GLOSTFM?tab=readme-ov-file)            |


---


## 🧠 CNN-Based Models


| Abbreviation | Paper                                                                                                                                                                                                                   | Year | Dataset                  |                                                    Code                                                    |
| :----------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--: | ------------------------ | :--------------------------------------------------------------------------------------------------------: |
|   STFDCNN    | [Spatiotemporal Satellite Image Fusion Using Deep Convolutional Neural Networks](https://ieeexplore.ieee.org/document/8291042?arnumber=8291042)                                                                         | 2018 | CIA, LGC                 |                                         [Link](STFDCNN/stfdcnn.py)                                         |
|    DCSTFN    | [Deriving High Spatiotemporal Remote Sensing Images Using Deep Convolutional Network](https://www.mdpi.com/2072-4292/10/7/1066)                                                                                         | 2018 | MODIS, Landsat           |                                [Link](https://github.com/theonegis/dcstfn)                                 |
|    STFNet    | [StfNet: A Two-Stream Convolutional Neural Network for Spatiotemporal Image Fusion](https://ieeexplore.ieee.org/document/8693668)                                                                                       | 2019 | Landsat, MODIS           |                                          [Link](STFNet/stfnet.py)                                          |
|   EDCSTFN    | [An Enhanced Deep Convolutional Model for Spatiotemporal Image Fusion](https://www.mdpi.com/2072-4292/11/24/2898)                                                                                                       | 2019 | MODIS, Landsat           |                                [Link](https://github.com/theonegis/edcstfn)                                |
|    STTFN     | [Spatiotemporal Fusion of Land Surface Temperature Based on a Convolutional Neural Network](https://ieeexplore.ieee.org/document/9115890)                                                                               | 2021 | **LST** (Landsat, MODIS) |                            [Link](https://github.com/Todd-C-Goldfarb/STTFN-OSU)                            |
|    MUSTFN    | [MUSTFN: A spatiotemporal fusion method for multi-scale and multi-sensor remote sensing images based on a convolutional neural network](https://www.sciencedirect.com/science/article/pii/S1569843222003016?via%3Dihub) | 2022 | Landsat-7, GaoFen-1      |                                  [Link](https://github.com/qpyeah/MUSTFN)                                  |
|   DenseSTF   | [Deep Learning-Based Spatiotemporal Data Fusion Using a Patch-to-Pixel Mapping Strategy and Model Comparisons](https://ieeexplore.ieee.org/document/9721293)                                                            | 2022 | CIA, LGC                 |                              [Link](https://github.com/sysu-xin-lab/DenseSTF)                              |
|   STF-EGFA   | [STF-EGFA: A Remote Sensing Spatiotemporal Fusion Network with Edge-Guided Feature Attention](https://www.mdpi.com/2072-4292/14/13/3057)                                                                                | 2022 | AHB, Daxing, Tianjin     |                     [Link](https://github.com/FZUcheng123/STF-EGFA?tab=readme-ov-file)                     |
|     CAFE     | [CAFE: A Cross-Attention Based Adaptive Weighting Fusion Network for MODIS and Landsat Spatiotemporal Fusion](https://ieeexplore.ieee.org/document/10153669?arnumber=10153669)                                          | 2023 | Landsat, MODIS           |                       [Link](https://github.com/LiupengLin/CAFE?tab=readme-ov-file)                        |
|  ECPW-STFN   | [Enhanced wavelet based spatiotemporal fusion networks using cross-paired remote sensing images](https://www.sciencedirect.com/science/article/abs/pii/S092427162400176X?via%3Dihub)                                    | 2024 | CIA, Daxing              |                             [Link](https://github.com/lixinghua5540/ECPW-STFN)                             |
|  RCAN-FSDAF  | [A Novel Remote Sensing Spatiotemporal Data Fusion Framework Based on the Combination of Deep-Learning Downscaling and Traditional Fusion Algorithm](https://ieeexplore.ieee.org/document/10480541)                     | 2024 | Landsat 8 OLI, MODIS     | [RCAN](https://github.com/yulunzhang/RCAN)+[FSDAF](https://xzhu-lab.github.io/Pride/Open-Source-Code.html) |
|     SDCS     | [Semiblind Compressed Sensing: A Bidirectional-Driven Method for Spatiotemporal Fusion of Remote Sensing Images](https://ieeexplore.ieee.org/document/10696963?arnumber=10696963)                                       | 2024 | CIA, LGC, AHB, Tianjin   |                                   [Link](https://github.com/yc-cui/SDCS)                                   |



---


## 🔍 Transformer-Based Models


| Abbreviation | Paper                                                                                                                                                                                             | Year | Dataset                   |                         Code                         |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--: | ------------------------- | :--------------------------------------------------: |
| SwinSTFM     | [SwinSTFM: Remote Sensing Spatiotemporal Fusion Using Swin Transformer](https://ieeexplore.ieee.org/document/9795183?arnumber=9795183)                                                            | 2022 | CIA, LGC, AHB             |  [Link](https://github.com/LouisChen0104/swinstfm)   |
| STM-STFNet   | [A Dual-Perspective Spatiotemporal Fusion Model for Remote Sensing Images by Discriminative Learning of the Spatial and Temporal Mapping](https://ieeexplore.ieee.org/abstract/document/10595407) | 2024 | LGC、CIA、DX                |    [Link](https://github.com/zhonhua/STM-STFNet)     |
| MGSFormer    | [MGSFformer: A Multi-Granularity Spatiotemporal Fusion Transformer for air quality prediction](https://www.sciencedirect.com/science/article/abs/pii/S1566253524003853)                           | 2025 | Beijingsites, Chinacities | [Link](https://github.com/GestaltCogTeam/MGSFformer) |
| THSTNet      | [A Two-Stage Hierarchical Spatiotemporal Fusion Network for Land Surface Temperature With Transformer](https://ieeexplore.ieee.org/document/10930886)                                             | 2025 | LST(Landsat, MODIS)       |   [Link](https://github.com/HuPengHua2021/THSTNet)   |

---

## 🎨 GAN-Based Models

| Abbreviation | Paper                                                                                                                                                                                   | Year | Dataset         |                       Code                       |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--: | --------------- | :----------------------------------------------: |
| STFGAN       | [Remote Sensing Image Spatiotemporal Fusion Using a Generative Adversarial Network](https://ieeexplore.ieee.org/document/9159647)                                                       | 2021 | CIA, LGC        |                  [Link](STFGAN)                  |
| MLFF-GAN     | [MLFF-GAN: A Multilevel Feature Fusion With GAN for Spatiotemporal Remote Sensing Images](https://ieeexplore.ieee.org/document/9540272)                                                 | 2022 | CIA, LGC        |  [Link](https://github.com/songbingze/MLFF-GAN)  |
| GAN-STFM     | [A Flexible Reference-Insensitive Spatiotemporal Fusion Model for Remote Sensing Images Using Conditional Generative Adversarial Network](https://ieeexplore.ieee.org/document/9336033) | 2022 | CIA, LGC        |   [Link](https://github.com/theonegis/ganstfm)   |
| OPGAN        | [Remote Sensing Image Spatiotemporal Fusion via a Generative Adversarial Network With One Prior Image Pair](https://ieeexplore.ieee.org/abstract/document/9765452)                      | 2022 | CIA, LGC        |                  [Link](OPGAN)                   |
| DCDGAN-STF   | [DCDGAN-STF: A Multiscale Deformable Convolution Distillation GAN for Remote Sensing Image Spatiotemporal Fusion](https://ieeexplore.ieee.org/document/10707182)                        | 2024 | CIA, LGC, Wuhan | [Link](https://github.com/zhangyanxa/DCDGAN-STF) |


---

## 🔀 Other Models

| Abbreviation | Paper                                                                                                                                                                                                                |   Network    | Year | Dataset                 |                          Code                           |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------: | :--: | ----------------------- | :-----------------------------------------------------: |
| STFMLP       | [StfMLP: Spatiotemporal Fusion Multilayer Perceptron for Remote-Sensing Images](https://ieeexplore.ieee.org/document/9999642)                                                                                        |     MLP      | 2023 | CIA, LGC                | [Link](https://github.com/luhailaing-max/StfMLP-master) |
| DSTFNet      | [Improving agricultural field parcel delineation with a dual branch spatiotemporal fusion network by integrating multimodal satellite data](https://www.sciencedirect.com/science/article/abs/pii/S0924271623002630) | ConvLSTM、CNN | 2023 | GF-2, Sentinel-2        |       [Link](https://github.com/BruceKai/DSTFNet)       |
| STFDiff      | [STFDiff: Remote sensing image spatiotemporal fusion with diffusion models](https://www.sciencedirect.com/science/article/abs/pii/S1566253524002835?via%3Dihub)                                                      |  Diffusion   | 2024 | CIA, LGC                |         [Link](https://github.com/prowDIY/STF)          |
| DiffSTSF     | [Diffusion models for spatio-temporal-spectral fusion of homogeneous Gaofen-1 satellite platforms](https://www.sciencedirect.com/science/article/pii/S1569843224001067)                                              |  Diffusion   | 2024 | Gaofen-1 (PAN, MS, WFV) |      [Link](https://github.com/isstncu/gf1fusion)       |


---

## 🎯 Datasets & Benchmarks

| **Dataset** | **Source**              | **Resolution**        | **Region**          |                                      Download                                      |
| ----------- | ----------------------- | --------------------- | ------------------- | :--------------------------------------------------------------------------------: |
| CIA         | Landsat, MODIS          | 30m, 500m, 16 days    | Coleambally, AU     |                [Link](https://data.csiro.au/collection/csiro:5846)                 |
| LGC         | Landsat-5 TM, MODIS     | 30m, 500m, 16 days    | Lower Gwydir, AU    |                [Link](https://data.csiro.au/collection/csiro:5846)                 |
| MOD09GA     | MODIS                   | 500m, Monthly         | North China Plain   |                  [Link](https://ladsweb.modaps.eosdis.nasa.gov/)                   |
| BC          | Sentinel-2 MSI, S3 OLCI | 10m, 300m, Monthly    | SW Butte County, CA | [Link](https://www.esa.int/Applications/Observing_the_Earth/Copernicus/Sentinel-2) |
| IC          | Sentinel-2 MSI, S3 OLCI | 10m, 300m, Monthly    | Imperial County, CA | [Link](https://www.esa.int/Applications/Observing_the_Earth/Copernicus/Sentinel-2) |
| OISST       | AVHRR, Buoy, Ship       | 0.25° × 0.25°, Daily  | Global Ocean        |        [Link](https://www.ncei.noaa.gov/products/optimum-interpolation-sst)        |
| OSTIA       | Multi-sat IR, MW, Buoy  | 0.05° × 0.05°, Daily  | Global Ocean        |   [Link](https://data.marine.copernicus.eu/products?option=com_csw&task=results)   |
| G1SST       | Geo, Polar Sats         | 0.01° × 0.01°, Daily  | Global Ocean        |    [Link](https://podaac.jpl.nasa.gov/dataset/JPL_OUROCEAN-L4UHfnd-GLOB-G1SST)     |
| EARS        | ECMWF Model             | 0.25° × 0.25°, Hourly | Global Ocean        |                           [Link](https://rda.ucar.edu/)                            |
| In-situ     | Buoy Measurements       | 16 Stations, Hourly   | Korean waters       |                        [Link](https://www.nifs.go.kr/kodc)                         |
| TRMM        | NASA GSFC PPS           | 0.25°, 3-hourly       | 50°N–50°S           |                    [Link](https://gpm.nasa.gov/data/directory)                     |
| GridSat     | NOAA                    | 0.07°, 3-hourly       | 70°S–70°N           |         [Link](https://www.ncei.noaa.gov/products/satellite/gridded-data)          |
| DEM         | USGS, NASA SRTM         | 90m, N/A              | 60°N–56°S           |                    [Link](https://srtm.csi.cgiar.org/srtmdata/)                    |
| Rain        | CMDC (China)            | Point, 12-hourly      | China               |                            [Link](https://data.cma.cn/)                            |
| S2          | Sentinel-2              | 10m, 5-day revisit    | Dafeng, China       |                        [Link](https://scilb.copernicus.eu/)                        |
| GOCI-II     | GOCI-II Satellite       | 500m, hourly          | Dafeng, China       |                       [Link](https://www.nosc.go.kr/main.do)                       |
| Wuhan       | GF, Landsat             | 8m, 30m               | Wuhan, China        |               [Link](https://github.com/lixinghua5540/Wuhan-dataset)               |
| Daxing      | LS8 OLI, MODIS          | 30m, 500m, 8 days     | Daxing, Beijing     |       [Link](https://pan.baidu.com/s/1ymgud6tnY6XB5CTCXPUfnw#list/path=%2F)        |
| AHB         | LS8 OLI, MOD09GA        | 30m, 500m, 16 days    | Ar Horqin Banner    |       [Link](https://pan.baidu.com/s/1ymgud6tnY6XB5CTCXPUfnw#list/path=%2F)        |
| Tianjin     | LS8 OLI, MOD02HKM       | 30m, 500m, 16 days    | Tianjin, China      |       [Link](https://pan.baidu.com/s/1ymgud6tnY6XB5CTCXPUfnw#list/path=%2F)        |
| Terra       | Multi-source            | 0.1°, 3-hourly        | Global              |              [Link](https://github.com/CityMind-Lab/NeurIPS24-Terra)               |
| E-SMILE     | Landsat-8               | 30m, 500m, 16 days    | Global              |        [Link](https://www.kaggle.com/datasets/yuxiawhu/extra-data-in-smile)        |



---

## 🤝 Contribution
If you have any questions, suggestions, or would like to contribute additional resources to this project, please  free to contact me via WeChat (ID: Arborise) or email at arborise@163.com.


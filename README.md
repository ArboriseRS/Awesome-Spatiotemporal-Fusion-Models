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


| Abbreviation | Paper                                                                                                                                                                                                               | Year |  Method  |                              Code                              |
| :----------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--: | :------: | :------------------------------------------------------------: |
|    STARFM    | [On the Blending of the Landsat and MODIS Surface Reflectance: Predicting Daily Landsat Surface Reflectance](https://ieeexplore.ieee.org/document/1661809)                                                          | 2006 | WR-based |          [Link](https://github.com/nmileva/starfm4py)          |
|   ESTARFM    | [An enhanced spatial and temporal adaptive reflectance fusion model for complex heterogeneous regions](https://www.sciencedirect.com/science/article/abs/pii/S0034425710001884?via%3Dihub#preview-section-snippets) | 2010 | WR-based | [Link](https://xzhu-lab.github.io/Pride/Open-Source-Code.html) |
|    FSDAF     | [A flexible spatiotemporal method for fusing satellite images with different resolutions](https://www.sciencedirect.com/science/article/abs/pii/S0034425715302042?via%3Dihub)                                       | 2016 |  Hybrid  | [Link](https://xzhu-lab.github.io/Pride/Open-Source-Code.html) |
|    Fit-FC    | [Spatio-temporal fusion for daily Sentinel-2 images](https://www.sciencedirect.com/science/article/abs/pii/S0034425717305096?via%3Dihub)                                                                            | 2018 | WR-based |         [Link](https://github.com/qunmingwang/Fit-FC)          |
|    SPSTFM    | [Spatiotemporal reflectance fusion via sparse representation](https://ieeexplore.ieee.org/document/6169983)                                                                                                         | 2012 |          |                              Link                              |




---

## 🧠 CNN-Based Models
| Abbreviation | Paper                                                                                                                                                                                                                   | Year | Dataset                  |                             Code                              |
| :----------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--: | ------------------------ | :-----------------------------------------------------------: |
|   STFDCNN    | [Spatiotemporal Satellite Image Fusion Using Deep Convolutional Neural Networks](https://ieeexplore.ieee.org/document/8291042?arnumber=8291042)                                                                         | 2018 | CIA, LGC                 |                  [Link](STFDCNN/stfdcnn.py)                   |
|    DCSTFN    | [Deriving High Spatiotemporal Remote Sensing Images Using Deep Convolutional Network](https://www.mdpi.com/2072-4292/10/7/1066)                                                                                         | 2018 | MODIS, Landsat           |          [Link](https://github.com/theonegis/dcstfn)          |
|    STFNet    | [StfNet: A Two-Stream Convolutional Neural Network for Spatiotemporal Image Fusion](https://ieeexplore.ieee.org/document/8693668)                                                                                       | 2019 | Landsat, MODIS           |                   [Link](STFNet/stfnet.py)                    |
|   EDCSTFN    | [An Enhanced Deep Convolutional Model for Spatiotemporal Image Fusion](https://www.mdpi.com/2072-4292/11/24/2898)                                                                                                       | 2019 | MODIS, Landsat           |         [Link](https://github.com/theonegis/edcstfn)          |
|   STF3DCNN   | [A Fast Three-Dimensional Convolutional Neural Network-Based Spatiotemporal Fusion Method (STF3DCNN) Using a Spatial-Temporal-Spectral Dataset](https://www.mdpi.com/2072-4292/12/23/3888)                              | 2020 | CIA, LGC, RDT            |                             Link                              |
|    STTFN     | [Spatiotemporal Fusion of Land Surface Temperature Based on a Convolutional Neural Network](https://ieeexplore.ieee.org/document/9115890)                                                                               | 2021 | **LST** ：Landsat, MODIS  |     [Link](https://github.com/Todd-C-Goldfarb/STTFN-OSU)      |
|    MCDNet    | [A Multi-Cooperative Deep Convolutional Neural Network for Spatiotemporal Satellite Image Fusion](https://ieeexplore.ieee.org/document/9540272)                                                                         | 2021 | CIA, LGC                 |                             Link                              |
|     MOST     |                                                                                                                                                                                                                         | 2021 | Landsat-8, MODIS         |                             Link                              |
|    MUSTFN    | [MUSTFN: A spatiotemporal fusion method for multi-scale and multi-sensor remote sensing images based on a convolutional neural network](https://www.sciencedirect.com/science/article/pii/S1569843222003016?via%3Dihub) | 2022 | Landsat-7, GaoFen-1      |           [Link](https://github.com/qpyeah/MUSTFN)            |
|   DenseSTF   | [Deep Learning-Based Spatiotemporal Data Fusion Using a Patch-to-Pixel Mapping Strategy and Model Comparisons](https://ieeexplore.ieee.org/document/9721293)                                                            | 2022 | CIA, LGC                 |       [Link](https://github.com/sysu-xin-lab/DenseSTF)        |
|   STF-EGFA   |                                                                                                                                                                                                                         | 2022 | AHB, Daxing, Tianjin     |                             Link                              |
|   HCNNNet    |                                                                                                                                                                                                                         | 2022 | CIA, LGC, Daxing         |                             Link                              |
|    MACNN     | [Spatiotemporal image fusion using multiscale attention-aware two-stream convolutional neural networks](https://www.sciencedirect.com/science/article/pii/S2666017222000244?via%3Dihub)                                 | 2022 | Landsat, MODIS           |                             Link                              |
|     CAFE     | [CAFE: A Cross-Attention Based Adaptive Weighting Fusion Network for MODIS and Landsat Spatiotemporal Fusion](https://ieeexplore.ieee.org/document/10153669?arnumber=10153669)                                          | 2023 | Landsat, MODIS           | [Link](https://github.com/LiupengLin/CAFE?tab=readme-ov-file) |
|  ECPW-STFN   | [Enhanced wavelet based spatiotemporal fusion networks using cross-paired remote sensing images](https://www.sciencedirect.com/science/article/abs/pii/S092427162400176X?via%3Dihub)                                    | 2024 | CIA, Daxing              |      [Link](https://github.com/lixinghua5540/ECPW-STFN)       |
|    MLKNet    | [MLKNet: Multi-Stage for Remote Sensing Image Spatiotemporal Fusion Network Based on a Large Kernel Attention](https://ieeexplore.ieee.org/document/10342633)                                                           | 2024 | CIA, DX, SW              |                             Link                              |
|  RCAN-FSDAF  |                                                                                                                                                                                                                         | 2024 | Landsat 8 OLI, MODIS13Q1 |                             Link                              |
|    CTSTFM    |                                                                                                                                                                                                                         | 2024 | CIA, DX                  |                             Link                              |


---


## 🔍 Transformer-Based Models

| Abbreviation | Paper                                                                                                                                                                                             | Year | Dataset                    |                         Code                         |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--: | -------------------------- | :--------------------------------------------------: |
| SwinSTFM     | [SwinSTFM: Remote Sensing Spatiotemporal Fusion Using Swin Transformer](https://ieeexplore.ieee.org/document/9795183?arnumber=9795183)                                                            | 2022 | CIA, LGC, AHB              |  [Link](https://github.com/LouisChen0104/swinstfm)   |
| TTSFNet      |                                                                                                                                                                                                   | 2024 | SST, SSS, SSHA, SSWA, SSTA |                         Link                         |
| STINet       |                                                                                                                                                                                                   | 2024 | Landsat-8, Sentinel-2      |                         Link                         |
| STFTN        | [STINet: Vegetation Changes Reconstruction Through a Transformer-Based Spatiotemporal Fusion Approach in Remote Sensing](https://ieeexplore.ieee.org/document/10636344)                           | 2024 | CMIP6, SODA, GODAS, NMME   |                         Link                         |
| STM-STFNet   | [A Dual-Perspective Spatiotemporal Fusion Model for Remote Sensing Images by Discriminative Learning of the Spatial and Temporal Mapping](https://ieeexplore.ieee.org/abstract/document/10595407) | 2024 | LGC、CIA、DX                 |    [Link](https://github.com/zhonhua/STM-STFNet)     |
| MGSFormer    | [MGSFformer: A Multi-Granularity Spatiotemporal Fusion Transformer for air quality prediction](https://www.sciencedirect.com/science/article/abs/pii/S1566253524003853)                           | 2025 | Beijingsites, Chinacities  | [Link](https://github.com/GestaltCogTeam/MGSFformer) |

---

## 🎨 GAN-Based Models

| Abbreviation | Paper                                                                                                                                                                                   | Year | Dataset         |                       Code                       |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--: | --------------- | :----------------------------------------------: |
| MLFF-GAN     | [MLFF-GAN: A Multilevel Feature Fusion With GAN for Spatiotemporal Remote Sensing Images](https://ieeexplore.ieee.org/document/9540272)                                                 | 2022 | CIA, LGC        |  [Link](https://github.com/songbingze/MLFF-GAN)  |
| GAN-STFM     | [A Flexible Reference-Insensitive Spatiotemporal Fusion Model for Remote Sensing Images Using Conditional Generative Adversarial Network](https://ieeexplore.ieee.org/document/9336033) | 2022 | CIA, LGC        |   [Link](https://github.com/theonegis/ganstfm)   |
| OPGAN        | [Remote Sensing Image Spatiotemporal Fusion via a Generative Adversarial Network With One Prior Image Pair](https://ieeexplore.ieee.org/abstract/document/9765452)                      | 2022 | CIA, LGC        |                  [Link](OPGAN)                   |
| SS-STFM      |                                                                                                                                                                                         | 2024 | LGC, BJGF6      |                       Link                       |
| HPLTS-GAN    | [HPLTS-GAN: A High-Precision Remote Sensing Spatiotemporal Fusion Method Based on Low Temporal Sensitivity](https://ieeexplore.ieee.org/document/10559990)                              | 2024 | CIA, LGC        |                       Link                       |
| DCDGAN-STF   | [DCDGAN-STF: A Multiscale Deformable Convolution Distillation GAN for Remote Sensing Image Spatiotemporal Fusion](https://ieeexplore.ieee.org/document/10707182)                        | 2024 | CIA, LGC, Wuhan | [Link](https://github.com/zhangyanxa/DCDGAN-STF) |


---

## 🔀 Other Models


| Abbreviation | Paper                                                                                                                                                                             |     Network     | Year | Dataset                            |                     Code                     |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------: | :--: | ---------------------------------- | :------------------------------------------: |
| MFDGCN       |                                                                                                                                                                                   |    Diffusion    | 2022 | PeMS_BAY                           |                     Link                     |
| STFDiff      | [STFDiff: Remote sensing image spatiotemporal fusion with diffusion models](https://www.sciencedirect.com/science/article/abs/pii/S1566253524002835?via%3Dihub)                   |    Diffusion    | 2024 | CIA, LGC                           |    [Link](https://github.com/prowDIY/STF)    |
| DiffSTF      |                                                                                                                                                                                   |    Diffusion    | 2024 | CIA, LGC                           |                     Link                     |
| DiffSTSF     |                                                                                                                                                                                   |    Diffusion    | 2024 | Gaofen-1 (PAN, MS, WFV)            | [Link](https://github.com/isstncu/gf1fusion) |
| CNN-LSTM     | [A spatiotemporal deep fusion model for merging satellite and gauge precipitation in China](https://www.sciencedirect.com/science/article/abs/pii/S0022169420301244?via%3Dihub)   | Sequence Models | 2020 | TRMM, GridSat-B1, DEM, Rain Gauges |                     Link                     |
| ConvLSTM     |                                                                                                                                                                                   | Sequence Models | 2024 | ERA5-land, GPM                     |                     Link                     |
| Geo-BiLSTMA  |                                                                                                                                                                                   | Sequence Models | 2024 | Xi'an                              |                     Link                     |
| STHGCN       |                                                                                                                                                                                   |     Others      | 2022 | METR-LA, PEMS-BAY, Solar Energy    |                     Link                     |
| MSFusion     | [MSFusion: Multistage for Remote Sensing Image Spatiotemporal Fusion Based on Texture Transformer and Convolutional Neural Network](https://ieeexplore.ieee.org/document/9786792) |     Others      | 2022 | CIA, LGC, DX                       |                     Link                     |
| STFMLP       | [StfMLP: Spatiotemporal Fusion Multilayer Perceptron for Remote-Sensing Images](https://ieeexplore.ieee.org/document/9999642)                                                     |     Others      | 2023 | CIA, LGC                           | [Link](https://github.com/isstncu/gf1fusion) |
| DSTFNet      |                                                                                                                                                                                   |     Others      | 2023 | GF-2, Sentinel-2                   |                     Link                     |
| SDCS         | [Semiblind Compressed Sensing: A Bidirectional-Driven Method for Spatiotemporal Fusion of Remote Sensing Images](https://ieeexplore.ieee.org/document/10696963?arnumber=10696963) |     Others      | 2024 | CIA, LGC, AHB, Tianjin             |    [Link](https://github.com/yc-cui/SDCS)    |

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


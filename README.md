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


| Abbreviation | Paper                                                                                                                                                                                                                   | Year |  Method  |                     Code                     |
| :----------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--: | :------: | :------------------------------------------: |
|    STARFM    | **[On the Blending of the Landsat and MODIS Surface Reflectance: Predicting Daily Landsat Surface Reflectance](https://ieeexplore.ieee.org/document/1661809)**                                                          | 2006 | WR-based | [Link](https://github.com/nmileva/starfm4py) |
|   ESTARFM    | [**An enhanced spatial and temporal adaptive reflectance fusion model for complex heterogeneous regions**](https://www.sciencedirect.com/science/article/abs/pii/S0034425710001884?via%3Dihub#preview-section-snippets) |      | WR-based |                     Link                     |



---

## 🧠 CNN-Based Models
| Abbreviation | Paper                                                                                                                                           | Year | Dataset                  |                        Code                        |
| :----------: | ----------------------------------------------------------------------------------------------------------------------------------------------- | :--: | ------------------------ | :------------------------------------------------: |
|   STFDCNN    | [Spatiotemporal Satellite Image Fusion Using Deep Convolutional Neural Networks](https://ieeexplore.ieee.org/document/8291042?arnumber=8291042) | 2018 | CIA, LGC                 |                        Link                        |
|    STFNet    |                                                                                                                                                 | 2019 | Landsat, MODIS           |                        Link                        |
|   EDCSTFN    |                                                                                                                                                 | 2019 | MODIS, Landsat           |    [Link](https://github.com/theonegis/edcstfn)    |
|   STF3DCNN   |                                                                                                                                                 | 2020 | CIA, LGC, RDT            |                        Link                        |
|    STTFN     |                                                                                                                                                 | 2021 | Landsat, MODIS           |                        Link                        |
|    MCDNet    |                                                                                                                                                 | 2021 | CIA, LGC                 |                        Link                        |
|     MOST     |                                                                                                                                                 | 2021 | Landsat-8, MODIS         |                        Link                        |
|    MUSTFN    |                                                                                                                                                 | 2022 | Landsat-7, GaoFen-1      |      [Link](https://github.com/qpyeah/MUSTFN)      |
|   DenseSTF   |                                                                                                                                                 | 2022 | CIA, LGC                 |  [Link](https://github.com/sysu-xin-lab/DenseSTF)  |
|   STF-EGFA   |                                                                                                                                                 | 2022 | AHB, Daxing, Tianjin     |                        Link                        |
|   HCNNNet    |                                                                                                                                                 | 2022 | CIA, LGC, Daxing         |                        Link                        |
|    MACNN     |                                                                                                                                                 | 2022 | Landsat, MODIS           |                        Link                        |
|  ECPW-STFN   |                                                                                                                                                 | 2024 | CIA, Daxing              | [Link](https://github.com/lixinghua5540/ECPW-STFN) |
|    MLKNet    |                                                                                                                                                 | 2024 | CIA, DX, SW              |                        Link                        |
|  RCAN-FSDAF  |                                                                                                                                                 | 2024 | Landsat 8 OLI, MODIS13Q1 |                        Link                        |
|    CTSTFM    |                                                                                                                                                 | 2024 | CIA, DX                  |                        Link                        |


---


## 🔍 Transformer-Based Models

| Model     | Paper | Year | Dataset                    |                         Code                         |
| --------- | ----- | :--: | -------------------------- | :--------------------------------------------------: |
| SwinSTFM  |       | 2022 | CIA, LGC, AHB              |  [Link](https://github.com/LouisChen0104/swinstfm)   |
| TTSFNet   |       | 2024 | SST, SSS, SSHA, SSWA, SSTA |                         Link                         |
| STINet    |       | 2024 | Landsat-8, Sentinel-2      |                         Link                         |
| STFTN     |       | 2024 | CMIP6, SODA, GODAS, NMME   |                         Link                         |
| MGSFormer |       | 2025 | Beijingsites, Chinacities  | [Link](https://github.com/GestaltCogTeam/MGSFformer) |

---

## 🎨 GAN-Based Models

| Abbreviation | Paper | Year | Dataset         |                       Code                       |
| ------------ | ----- | :--: | --------------- | :----------------------------------------------: |
| MLFF-GAN     |       | 2022 | CIA, LGC        |  [Link](https://github.com/songbingze/MLFF-GAN)  |
| GAN-STFM     |       | 2022 | CIA, LGC        |   [Link](https://github.com/theonegis/ganstfm)   |
| SS-STFM      |       | 2024 | LGC, BJGF6      |                       Link                       |
| HPLTS-GAN    |       | 2024 | CIA, LGC        |                       Link                       |
| DCDGAN-STF   |       | 2024 | CIA, LGC, Wuhan | [Link](https://github.com/zhangyanxa/DCDGAN-STF) |


---

## 🔀 Other Models


| Abbreviation | Paper |     Network     | Year | Dataset                            |                     Code                     |
| ------------ | ----- | :-------------: | :--: | ---------------------------------- | :------------------------------------------: |
| MFDGCN       |       |    Diffusion    | 2022 | PeMS_BAY                           |                     Link                     |
| STFDiff      |       |    Diffusion    | 2024 | CIA, LGC                           |    [Link](https://github.com/prowDIY/STF)    |
| DiffSTF      |       |    Diffusion    | 2024 | CIA, LGC                           |                     Link                     |
| DiffSTSF     |       |    Diffusion    | 2024 | Gaofen-1 (PAN, MS, WFV)            | [Link](https://github.com/isstncu/gf1fusion) |
| CNN-LSTM     |       | Sequence Models | 2020 | TRMM, GridSat-B1, DEM, Rain Gauges |                     Link                     |
| ConvLSTM     |       | Sequence Models | 2024 | ERA5-land, GPM                     |                     Link                     |
| Geo-BiLSTMA  |       | Sequence Models | 2024 | Xi'an                              |                     Link                     |
| STHGCN       |       |     Others      | 2022 | METR-LA, PEMS-BAY, Solar Energy    |                     Link                     |
| MSFusion     |       |     Others      | 2022 | CIA, LGC, DX                       |                     Link                     |
| STFMLP       |       |     Others      | 2023 | CIA, LGC                           | [Link](https://github.com/isstncu/gf1fusion) |
| DSTFNet      |       |     Others      | 2023 | GF-2, Sentinel-2                   |                     Link                     |
| SDCS         |       |     Others      | 2024 | CIA, LGC, AHB, Tianjin             |    [Link](https://github.com/yc-cui/SDCS)    |

---

## 🎯 Datasets & Benchmarks

| **Dataset** | **Source**              | **Resolution**        | **Region**          | Download                                                                           |
| ----------- | ----------------------- | --------------------- | ------------------- | ---------------------------------------------------------------------------------- |
| CIA         | Landsat, MODIS          | 30m, 500m, 16 days    | Coleambally, AU     | [Link](https://data.csiro.au/collection/csiro:5846)                                |
| LGC         | Landsat-5 TM, MODIS     | 30m, 500m, 16 days    | Lower Gwydir, AU    | [Link](https://data.csiro.au/collection/csiro:5846)                                |
| MOD09GA     | MODIS                   | 500m, Monthly         | North China Plain   | [Link](https://ladsweb.modaps.eosdis.nasa.gov/)                                    |
| BC          | Sentinel-2 MSI, S3 OLCI | 10m, 300m, Monthly    | SW Butte County, CA | [Link](https://www.esa.int/Applications/Observing_the_Earth/Copernicus/Sentinel-2) |
| IC          | Sentinel-2 MSI, S3 OLCI | 10m, 300m, Monthly    | Imperial County, CA | [Link](https://www.esa.int/Applications/Observing_the_Earth/Copernicus/Sentinel-2) |
| OISST       | AVHRR, Buoy, Ship       | 0.25° × 0.25°, Daily  | Global Ocean        | [Link](https://www.ncei.noaa.gov/products/optimum-interpolation-sst)               |
| OSTIA       | Multi-sat IR, MW, Buoy  | 0.05° × 0.05°, Daily  | Global Ocean        | [Link](https://data.marine.copernicus.eu/products?option=com_csw&task=results)     |
| G1SST       | Geo, Polar Sats         | 0.01° × 0.01°, Daily  | Global Ocean        | [Link](https://podaac.jpl.nasa.gov/dataset/JPL_OUROCEAN-L4UHfnd-GLOB-G1SST)        |
| EARS        | ECMWF Model             | 0.25° × 0.25°, Hourly | Global Ocean        | [Link](https://rda.ucar.edu/)                                                      |
| In-situ     | Buoy Measurements       | 16 Stations, Hourly   | Korean waters       | Link                                                                               |
| TRMM        | NASA GSFC PPS           | 0.25°, 3-hourly       | 50°N–50°S           | [Link](https://gpm.nasa.gov/data/directory)                                        |
| GridSat     | NOAA                    | 0.07°, 3-hourly       | 70°S–70°N           | [Link](https://www.ncei.noaa.gov/products/satellite/gridded-data)                  |
| DEM         | USGS, NASA SRTM         | 90m, N/A              | 60°N–56°S           | [Link](https://srtm.csi.cgiar.org/srtmdata/)                                       |
| Rain        | CMDC (China)            | Point, 12-hourly      | China               | [Link](https://data.cma.cn/)                                                       |
| S2          | Sentinel-2              | 10m, 5-day revisit    | Dafeng, China       | Link                                                                               |
| GOCI-II     | GOCI-II Satellite       | 500m, hourly          | Dafeng, China       | [Link](https://www.nosc.go.kr/main.do)                                             |
| Wuhan       | GF, Landsat             | 8m, 30m               | Wuhan, China        | [Link](https://github.com/lixinghua5540/Wuhan-dataset)                             |
| Daxing      | LS8 OLI, MODIS          | 30m, 500m, 8 days     | Daxing, Beijing     | [Link](https://pan.baidu.com/s/1ymgud6tnY6XB5CTCXPUfnw#list/path=%2F)              |
| AHB         | LS8 OLI, MOD09GA        | 30m, 500m, 16 days    | Ar Horqin Banner    | [Link](https://pan.baidu.com/s/1ymgud6tnY6XB5CTCXPUfnw#list/path=%2F)              |
| Tianjin     | LS8 OLI, MOD02HKM       | 30m, 500m, 16 days    | Tianjin, China      | [Link](https://pan.baidu.com/s/1ymgud6tnY6XB5CTCXPUfnw#list/path=%2F)              |
| Terra       | Multi-source            | 0.1°, 3-hourly        | Global              | [Link](https://github.com/CityMind-Lab/NeurIPS24-Terra)                            |
| E-SMILE     | Landsat-8               | 30m, 500m, 16 days    | Global              | [Link](https://www.kaggle.com/datasets/yuxiawhu/extra-data-in-smile)               |


---

## 🤝 Contribution
If you have any questions, suggestions, or would like to contribute additional resources to this project, please  free to contact me via WeChat (ID: Arborise) or email at arborise@163.com.


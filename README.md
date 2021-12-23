# Open Satellite Image Cloud Detection Resources

Reference:
Zhiwei Li, Huanfeng Shen, Qihao Weng, Yuzhuo Zhang,Peng Dou, Liangpei Zhang. Cloud and Cloud Shadow Detection for Optical Satellite Imagery: Features, Algorithms, Validation, and Prospects. 2021

Contributors:
1. Zhiwei Li, Wuhan University
2. Yuzhuo Zhang, Wuhan University

**Open-source datasets for CCS detection**

| Name | Source | References | Descriptions | Link |
| --- | --- | --- | --- | --- |
| L7\_Irish | Landsat-7(30 m) | Scaramuzza et al., 2012; USGS., 2016a | Contains 206 Landsat-7 scenes from nine global latitude zones with manually generated masks, of which only 45 scenes are labeled for cloud shadows. | [Link](https://landsat.usgs.gov/landsat-7-cloud-cover-assessment-validation-data) |
| --- | --- | --- | --- | --- |
| L8\_SPARCS | Landsat-8(30 m) | Hughes and Hayes, 2014; USGS., 2016c | Contains 80 subsets of Landsat-8 scenes with a size of 1000×1000 pixels that are labeled for both clouds and cloud shadows. | [https://www.usgs.gov/core-science-systems/nli/landsat/spatial-procedures-automated-removal-cloud-and-shadow-sparcs](https://www.usgs.gov/core-science-systems/nli/landsat/spatial-procedures-automated-removal-cloud-and-shadow-sparcs) |
| L8\_Biome | Landsat-8(30 m) | Foga et al., 2017; USGS., 2016b | Contains 96 Landsat-8 scenes from eight global biomes with manually generated cloud masks, of which 32 scenes are labeled for cloud shadows. | [https://landsat.usgs.gov/landsat-8-cloud-cover-assessment-validation-data](https://landsat.usgs.gov/landsat-8-cloud-cover-assessment-validation-data) |
| 95-Cloud | Landsat-8(30 m) | Mohajerani and Saeedi, 2019 | Contains 95 Landsat-8 images and associated pixel-level cloud labels that is an extension of the previously established 38-Cloud dataset. | https://github.com/SorourMo/95-Cloud-An-Extension-to-38-Cloud-Dataset |
| Snow-Cloud Validation Masks | Landsat-8(30 m) | Stillinger and Collar, 2019 | Contains 13 Landsat-8 images and corresponding clouds and snow labels at mid-latitude mountainous regions. | https://zenodo.org/record/3240937 |
| RICE\_dataset | Landsat-8(30 m) | Lin et al., 2019 | Contains 450 Landsat-8 images and corresponding cloud-free images and cloud labels with a size of 512×512 pixels in one of two subsets of the dataset. | https://github.com/BUPTLdy/RICE\_DATASET |
| WHU Cloud Dataset | Landsat-8(30 m) | Ji et al., 2021 | Contains 7 Landsat-8 images and corresponding cloud-free historical images and cloud and shadow masks in six different regions. | http://gpcv.whu.edu.cn/data/WHU\_Cloud\_Dataset.html |
| S2-Hollstein | Sentinel-2(10 m) | Hollstein et al., 2016 | Consists 5,647,725 pixels based on images acquired over the entire globe with cloud, cirrus, snow, shadow, and water labels. | [https://git.gfz-potsdam.de/EnMAP/sentinel2\_manual\_classification\_clouds](https://git.gfz-potsdam.de/EnMAP/sentinel2_manual_classification_clouds) |
| S2-BaetensHagolle | Sentinel-2(10 m) | Baetens et al., 2018, 2019 | Provides cloud masks for 38 Sentinel-2 scenes selected in 2017 or 2018, each with cloud and cloud shadow labels. | [https://zenodo.org/record/1460961](https://zenodo.org/record/1460961#.YN0zgbFoB3t) |
| T-S2/T-PS | Sentinel-2(10 m)PlanetScope(3 m) | Shendryk et al., 2019 | Contains 4,993 Sentinel-2 and 4,943 PlanetScope subscenes with a size of 512×512 pixels and only RGB and NIR bandsover the Wet Tropics of Australia, each is labeled at the block level. | https://data.mendeley.com/datasets/6gdybpjnwh/1 |
| Sentinel-2 Cloud Mask Catalogue | Sentinel-2(10 m) | Francis et al., 2020 | Comprises 20 m resolution cloud masks for 513 subscenes, of which 424 subscenes are labeled for cloud shadows. | [https://zenodo.org/record/4172871](https://zenodo.org/record/4172871) |
| Sentinel-2 KappaZeta | Sentinel-2(10 m) | Domnich et al., 2021 | Contains 4403 labeled image blocks with a size of 512×512 pixels from 155 Sentinel-2 images over the Northern European terrestrial area. | https://zenodo.org/record/5095024 |
| WHUS2-CD | Sentinel-2(10 m) | Li et al., 2021 | Contains 32 Sentinel-2 images distributed in Mainland China and its reference cloud masks labeled at 10 m resolution. | [https://github.com/Neooolee/WHUS2-CD](https://github.com/Neooolee/WHUS2-CD) |
| GF1\_WHU | Gaofen-1 WFV(16 m) | Li et al., 2017 | Contains 108 globally distributed GF-1 WFV scenes and their manually labeled cloud and cloud shadow masks. | [http://sendimage.whu.edu.cn/en/mfc-validation-data](http://sendimage.whu.edu.cn/en/mfc-validation-data) |
| Levir\_CS | Gaofen-1 WFV(16 m) | Wu et al., 2021 | Contains 4,168 globally distributed Gaofen-1 WFV scenes (down sampled to 160 m resolution) and the corresponding geographical data, cloud, and snow labels. | https://github.com/permanentCH5/GeoInfoNet |
| WDCD dataset | Gaofen-1 PMS(8 m)Ziyuan-3 MUX(5.8 m) | Li et al., 2020 | Contains over 200,000 globally distributed Gaofen-1 image blocks labeled at the block level for training and 30 Gaofen-1 and Ziyuan-3 scenes labeled at the pixel level for validation and testing. | https://github.com/weichenrs/WDCD |
| N/A | Gaofen series(N/A) | Sun et al., 2020 | Contains 745 paired NIR-R-G composited images and corresponding pixel-level labels with a size of 256×256 pixels. | https://bhpan.buaa.edu.cn/#/link/DDC7765A5A049E0F9A0DAD0E9F7692C5 |
| AIR-CD | Gaofen-2 PMS(4 m) | He et al., 2021 | Contains 34 Gaofen-2 full images and the corresponding cloud labels distributed at different regions of China. | https://github.com/AICyberTeam/AIR-CD |
| HRC\_WHU | Google Earth(0.5 m to 15 m) | Li et al., 2019 | Comprises 150 globally distributed high-resolution images (0.5 m to 15 m resolution, three RGB channels) and the corresponding cloud masks. | [http://sendimage.whu.edu.cn/en/hrc\_whu](http://sendimage.whu.edu.cn/en/hrc_whu/) |

**Open-source tools for CCS detection**

| Name | Applicable images (mainly) | References | Descriptions (data and method) | Link |
| Fmask | Landsat 4-8Sentinel-2 | Zhu et al., 2012 &amp; 2015 | Mono-temporal imagePhysical rule based | [https://github.com/GERSL/Fmask](https://github.com/GERSL/Fmask) |
| Tmask | Landsat 4-8 | Zhu and Woodcock, 2014b | Multi-temporal imagesTemporal change based | [https://github.com/GERSL/Tmask](https://github.com/GERSL/Tmask) |
| MSScvm | Landsat MSS | Braaten et al., 2015 | Multi-source dataPhysical rule based | [https://github.com/jdbcode/MSScvm](https://github.com/jdbcode/MSScvm) |
| MFmask | Landsat 4-8 | Qiu et al., 2017 | Multi-source dataPhysical rule based | https://github.com/qsly09/MFmask |
| MCM-GEE | Landsat-8 | Mateo-García et al., 2018 | Multi-temporal imagesTemporal change based | https://github.com/IPL-UV/ee\_ipl\_uv |
| Cloud-Net | Landsat-8 | Mohajerani and Saeedi, 2019 | Mono-temporal imageDL based | [https://github.com/SorourMo/Cloud-Net-A-semantic-segmentation-CNN-for-cloud-detection](https://github.com/SorourMo/Cloud-Net-A-semantic-segmentation-CNN-for-cloud-detection) |
| Cmask | Landsat-8 | Qiu et al., 2020 | Multi-temporal imagesTemporal change based | https://github.com/GERSL/Cmask |
| DAGANS | Landsat-8Proba-V | Mateo-Garcia et al., 2020 | Mono-temporal imageDL based | https://github.com/IPL-UV/pvl8dagans |
| FCNN | Landsats-8Sentinel-2 | López-Puigdollers et al., 2021 | Mono-temporal imageDL based | [https://github.com/IPL-UV/DL-L8S2-UV](https://github.com/IPL-UV/DL-L8S2-UV) |
| MAJA | Sentinel-2, VENµS, Landsat-8 | Hagolle et al., 2010 | Multi-temporal imageTemporal change based | https://github.com/CNES/MAJA |
| --- | --- | --- | --- | --- |
| cB4S2 | Sentinel-2 | Hollstein et al., 2016 | Mono-temporal imageMachine learning based | [https://github.com/hollstein/cB4S2](https://github.com/hollstein/cB4S2) |
| Sen2Cor | Sentinel-2 | Main-Knorn et al., 2017 | Mono-temporal imagePhysical rule based | [https://step.esa.int/main/snap-supported-plugins/sen2cor/](https://step.esa.int/main/snap-supported-plugins/sen2cor/) |
| s2cloudless | Sentinel-2 | Zupanc, 2017 | Mono-temporal imageMachine learning based | https://github.com/sentinel-hub/sentinel2-cloud-detector |
| FmaskCDI | Sentinel-2 | Frantz et al., 2018 | Mono-temporal imagePhysical rule based | [https://www.uni-trier.de/index.php?id=63673](https://www.uni-trier.de/index.php?id=63673) |
| KappaMask | Sentinel-2 | Domnich et al., 2021 | Mono-temporal imageDL based | https://github.com/kappazeta/cm\_predict |
| MFC | Gaofen-1 WFV | Li et al., 2017 | Mono-temporal imagePhysical rule based | [http://sendimage.whu.edu.cn/en/mfc](http://sendimage.whu.edu.cn/en/mfc) |
| --- | --- | --- | --- | --- |
| GeoInfoNet | Gaofen-1 WFV | Wu et al., 2021 | Mono-temporal imageDL based | https://github.com/permanentCH5/GeoInfoNet |
| N/A | HR images | Xie et al., 2017 | Mono-temporal imageDL based | [http://xfy.buaa.edu.cn/code.html](http://xfy.buaa.edu.cn/code.html) |
| --- | --- | --- | --- | --- |

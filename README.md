# Open Satellite Image Cloud Detection Resources (OpenSICDR)

We collects the latest open-source tools and datasets for cloud and cloud shadow detection, and launches the OpenSICDR project to promote the sharing of the latest research outputs (datasets and code/tools) of the field. If you would like to provide new resources as shown in the table below, please contact Zhiwei Li to add them, or submit an update request.

**Source:**

Zhiwei Li, Huanfeng Shen, Qihao Weng, Yuzhuo Zhang, Peng Dou, Liangpei Zhang. Cloud and Cloud Shadow Detection for Optical Satellite Imagery: Features, Algorithms, Validation, and Prospects. 2021. (Submitted)

**Contributors:**

1\. Zhiwei Li, Wuhan University, lizw(AT)whu.edu.cn

2\. Yuzhuo Zhang, Wuhan University, yuzhuozhang816(AT)whu.edu.cn

Last update: December 1, 2021


**Open-source datasets for cloud and cloud shadow detection**

| Name                            | Source                                  | References                            | Descriptions                                                                                                                                                                                        | Link                                                                                                                 |
|&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|
| L7_Irish                        | Landsat-7 (30 m)                        | Scaramuzza et al., 2012; USGS., 2016a | Contains 206 Landsat-7 scenes from nine global latitude zones with manually generated masks, of which only 45 scenes are labeled for cloud shadows.                                                 | <https://landsat.usgs.gov/landsat-7-cloud-cover-assessment-validation-data>                                          |
| L8_SPARCS                       | Landsat-8 (30 m)                        | Hughes and Hayes, 2014; USGS., 2016c  | Contains 80 subsets of Landsat-8 scenes with a size of 1000×1000 pixels that are labeled for both clouds and cloud shadows.                                                                         | <https://www.usgs.gov/core-science-systems/nli/landsat/spatial-procedures-automated-removal-cloud-and-shadow-sparcs> |
| L8_Biome                        | Landsat-8 (30 m)                        | Foga et al., 2017; USGS., 2016b       | Contains 96 Landsat-8 scenes from eight global biomes with manually generated cloud masks, of which 32 scenes are labeled for cloud shadows.                                                        | <https://landsat.usgs.gov/landsat-8-cloud-cover-assessment-validation-data>                                          |
| 95-Cloud                        | Landsat-8 (30 m)                        | Mohajerani and Saeedi, 2019           | Contains 95 Landsat-8 images and associated pixel-level cloud labels that is an extension of the previously established 38-Cloud dataset.                                                           | https://github.com/SorourMo/95-Cloud-An-Extension-to-38-Cloud-Dataset                                                |
| Snow-Cloud Validation Masks     | Landsat-8 (30 m)                        | Stillinger and Collar, 2019           | Contains 13 Landsat-8 images and corresponding clouds and snow labels at mid-latitude mountainous regions.                                                                                          | https://zenodo.org/record/3240937                                                                                    |
| RICE_dataset                    | Landsat-8 (30 m)                        | Lin et al., 2019                      | Contains 450 Landsat-8 images and corresponding cloud-free images and cloud labels with a size of 512×512 pixels in one of two subsets of the dataset.                                              | https://github.com/BUPTLdy/RICE_DATASET                                                                              |
| WHU Cloud Dataset               | Landsat-8 (30 m)                        | Ji et al., 2021                       | Contains 7 Landsat-8 images and corresponding cloud-free historical images and cloud and shadow masks in six different regions.                                                                     | http://gpcv.whu.edu.cn/data/WHU_Cloud_Dataset.html                                                                   |
| S2-Hollstein                    | Sentinel-2 (10 m)                       | Hollstein et al., 2016                | Consists 5,647,725 pixels based on images acquired over the entire globe with cloud, cirrus, snow, shadow, and water labels.                                                                        | <https://git.gfz-potsdam.de/EnMAP/sentinel2_manual_classification_clouds>                                            |
| S2-BaetensHagolle               | Sentinel-2 (10 m)                       | Baetens et al., 2018, 2019            | Provides cloud masks for 38 Sentinel-2 scenes selected in 2017 or 2018, each with cloud and cloud shadow labels.                                                                                    | [https://zenodo.org/record/1460961](https://zenodo.org/record/1460961#.YN0zgbFoB3t)                                  |
| T-S2/T-PS                       | Sentinel-2 (10 m) PlanetScope (3 m)     | Shendryk et al., 2019                 | Contains 4,993 Sentinel-2 and 4,943 PlanetScope subscenes with a size of 512×512 pixels and only RGB and NIR bands over the Wet Tropics of Australia, each is labeled at the block level.           | https://data.mendeley.com/datasets/6gdybpjnwh/1                                                                      |
| Sentinel-2 Cloud Mask Catalogue | Sentinel-2 (10 m)                       | Francis et al., 2020                  | Comprises 20 m resolution cloud masks for 513 subscenes, of which 424 subscenes are labeled for cloud shadows.                                                                                      | <https://zenodo.org/record/4172871>                                                                                  |
| Sentinel-2 KappaZeta            | Sentinel-2 (10 m)                       | Domnich et al., 2021                  | Contains 4403 labeled image blocks with a size of 512×512 pixels from 155 Sentinel-2 images over the Northern European terrestrial area.                                                            | https://zenodo.org/record/5095024                                                                                    |
| WHUS2-CD                        | Sentinel-2 (10 m)                       | Li et al., 2021                       | Contains 32 Sentinel-2 images distributed in Mainland China and its reference cloud masks labeled at 10 m resolution.                                                                               | <https://github.com/Neooolee/WHUS2-CD>                                                                               |
| GF1_WHU                         | Gaofen-1 WFV (16 m)                     | Li et al., 2017                       | Contains 108 globally distributed GF-1 WFV scenes and their manually labeled cloud and cloud shadow masks.                                                                                          | <http://sendimage.whu.edu.cn/en/mfc-validation-data>                                                                 |
| Levir_CS                        | Gaofen-1 WFV (16 m)                     | Wu et al., 2021                       | Contains 4,168 globally distributed Gaofen-1 WFV scenes (down sampled to 160 m resolution) and the corresponding geographical data, cloud, and snow labels.                                         | https://github.com/permanentCH5/GeoInfoNet                                                                           |
| WDCD dataset                    | Gaofen-1 PMS (8 m) Ziyuan-3 MUX (5.8 m) | Li et al., 2020                       | Contains over 200,000 globally distributed Gaofen-1 image blocks labeled at the block level for training and 30 Gaofen-1 and Ziyuan-3 scenes labeled at the pixel level for validation and testing. | https://github.com/weichenrs/WDCD                                                                                    |
| N/A                             | Gaofen series (N/A)                     | Sun et al., 2020                      | Contains 745 paired NIR-R-G composited images and corresponding pixel-level labels with a size of 256×256 pixels.                                                                                   | https://bhpan.buaa.edu.cn/\#/link/DDC7765A5A049E0F9A0DAD0E9F7692C5                                                   |
| AIR-CD                          | Gaofen-2 PMS (4 m)                      | He et al., 2021                       | Contains 34 Gaofen-2 full images and the corresponding cloud labels distributed at different regions of China.                                                                                      | https://github.com/AICyberTeam/AIR-CD                                                                                |
| HRC_WHU                         | Google Earth (0.5 m to 15 m)            | Li et al., 2019                       | Comprises 150 globally distributed high-resolution images (0.5 m to 15 m resolution, three RGB channels) and the corresponding cloud masks.                                                         | [http://sendimage.whu.edu.cn/en/hrc_whu](http://sendimage.whu.edu.cn/en/hrc_whu/)                                    |



**Open-source tools for cloud and cloud shadow detection**

|            | Name        | Applicable images (mainly)   | References                     | Descriptions  (data and method)             | Link                                                                                    |
|------------|-------------|------------------------------|--------------------------------|---------------------------------------------|-----------------------------------------------------------------------------------------|
| Landsat    | Fmask       | Landsat 4-8 Sentinel-2       | Zhu et al., 2012 & 2015        | Mono-temporal image Physical rule based     | <https://github.com/GERSL/Fmask>                                                        |
|            | Tmask       | Landsat 4-8                  | Zhu and Woodcock, 2014b        | Multi-temporal images Temporal change based | <https://github.com/GERSL/Tmask>                                                        |
|            | MSScvm      | Landsat MSS                  | Braaten et al., 2015           | Multi-source data Physical rule based       | <https://github.com/jdbcode/MSScvm>                                                     |
|            | MFmask      | Landsat 4-8                  | Qiu et al., 2017               | Multi-source data Physical rule based       | https://github.com/qsly09/MFmask                                                        |
|            | MCM-GEE     | Landsat-8                    | Mateo-García et al., 2018      | Multi-temporal images Temporal change based | https://github.com/IPL-UV/ee_ipl_uv                                                     |
|            | Cloud-Net   | Landsat-8                    | Mohajerani and Saeedi, 2019    | Mono-temporal image DL based                | <https://github.com/SorourMo/Cloud-Net-A-semantic-segmentation-CNN-for-cloud-detection> |
|            | Cmask       | Landsat-8                    | Qiu et al., 2020               | Multi-temporal images Temporal change based | https://github.com/GERSL/Cmask                                                          |
|            | DAGANS      | Landsat-8 Proba-V            | Mateo-Garcia et al., 2020      | Mono-temporal image DL based                | https://github.com/IPL-UV/pvl8dagans                                                    |
|            | FCNN        | Landsats-8 Sentinel-2        | López-Puigdollers et al., 2021 | Mono-temporal image DL based                | <https://github.com/IPL-UV/DL-L8S2-UV>                                                  |
| Sentinel-2 | MAJA        | Sentinel-2, VENµS, Landsat-8 | Hagolle et al., 2010           | Multi-temporal image Temporal change based  | https://github.com/CNES/MAJA                                                            |
|            | cB4S2       | Sentinel-2                   | Hollstein et al., 2016         | Mono-temporal image Machine learning based  | <https://github.com/hollstein/cB4S2>                                                    |
|            | Sen2Cor     | Sentinel-2                   | Main-Knorn et al., 2017        | Mono-temporal image Physical rule based     | <https://step.esa.int/main/snap-supported-plugins/sen2cor/>                             |
|            | s2cloudless | Sentinel-2                   | Zupanc, 2017                   | Mono-temporal image Machine learning based  | https://github.com/sentinel-hub/sentinel2-cloud-detector                                |
|            | FmaskCDI    | Sentinel-2                   | Frantz et al., 2018            | Mono-temporal image Physical rule based     | <https://www.uni-trier.de/index.php?id=63673>                                           |
|            | KappaMask   | Sentinel-2                   | Domnich et al., 2021           | Mono-temporal image DL based                | https://github.com/kappazeta/cm_predict                                                 |
| Gaofen     | MFC         | Gaofen-1 WFV                 | Li et al., 2017                | Mono-temporal image Physical rule based     | <http://sendimage.whu.edu.cn/en/mfc>                                                    |
|            | GeoInfoNet  | Gaofen-1 WFV                 | Wu et al., 2021                | Mono-temporal image DL based                | https://github.com/permanentCH5/GeoInfoNet                                              |
| Others     | N/A         | HR images                    | Xie et al., 2017               | Mono-temporal image DL based                | <http://xfy.buaa.edu.cn/code.html>                                                      |


**References:**

Baetens, L., Desjardins, C., Hagolle, O., 2019. Validation of copernicus
Sentinel-2 cloud masks obtained from MAJA, Sen2Cor, and FMask processors using
reference cloud masks generated with a supervised active learning procedure.
Remote Sensing 11, 1–25. https://doi.org/10.3390/rs11040433

Baetens, L., Hagolle, O., 2018. Sentinel-2 reference cloud masks generated by an
active learning method [Data set]. https://doi.org/10.5281/zenodo.1460961

Braaten, J.D., Cohen, W.B., Yang, Z., 2015. Automated cloud and cloud shadow
identification in Landsat MSS imagery for temperate ecosystems. Remote Sensing
of Environment 169, 128–138. https://doi.org/10.1016/j.rse.2015.08.006

Domnich, M., Sünter, I., Trofimov, H., Wold, O., Harun, F., Kostiukhin, A.,
Järveoja, M., Veske, M., Tamm, T., Voormansik, K., Olesk, A., Boccia, V.,
Longepe, N., Cadau, E.G., 2021. KappaMask: AI-Based Cloudmask Processor for
Sentinel-2. Remote Sensing 13, 4140.

Foga, S., Scaramuzza, P.L., Guo, S., Zhu, Z., Dilley, R.D., Beckmann, T.,
Schmidt, G.L., Dwyer, J.L., Joseph Hughes, M., Laue, B., 2017. Cloud detection
algorithm comparison and validation for operational Landsat data products.
Remote Sensing of Environment 194, 379–390.
https://doi.org/10.1016/j.rse.2017.03.026

Francis, A., Mrziglod, J., Sidiropoulos, P., Muller, J.-P., 2020. Sentinel-2
Cloud Mask Catalogue [Data set]. Zenodo. https://doi.org/10.5281/zenodo.4172871

Frantz, D., Haß, E., Uhl, A., Stoffels, J., Hill, J., 2018. Improvement of the
Fmask algorithm for Sentinel-2 images: Separating clouds from bright surfaces
based on parallax effects. Remote Sensing of Environment 215, 471–481.
https://doi.org/10.1016/j.rse.2018.04.046

Hagolle, O., Huc, M., Pascual, D.V., Dedieu, G., 2010. A multi-temporal method
for cloud detection, applied to FORMOSAT-2, VENμS, LANDSAT and SENTINEL-2
images. Remote Sensing of Environment 114, 1747–1755.
https://doi.org/10.1016/j.rse.2010.03.002

He, Q., Sun, X., Yan, Z., Fu, K., 2021. DABNet: Deformable Contextual and
Boundary-Weighted Network for Cloud Detection in Remote Sensing Images. IEEE
Transactions on Geoscience and Remote Sensing 1–16.
https://doi.org/10.1109/TGRS.2020.3045474

Hollstein, A., Segl, K., Guanter, L., Brell, M., Enesco, M., 2016. Ready-to-use
methods for the detection of clouds, cirrus, snow, shadow, water and clear sky
pixels in Sentinel-2 MSI images. Remote Sensing 8, 1–18.
https://doi.org/10.3390/rs8080666

Hughes, M.J., Hayes, D.J., 2014. Automated detection of cloud and cloud shadow
in single-date Landsat imagery using neural networks and spatial
post-processing. Remote Sensing 6, 4907–4926. https://doi.org/10.3390/rs6064907

Ji, S., Dai, P., Lu, M., Zhang, Y., 2021. Simultaneous Cloud Detection and
Removal from Bitemporal Remote Sensing Images Using Cascade Convolutional Neural
Networks. IEEE Transactions on Geoscience and Remote Sensing 59, 732–748.
https://doi.org/10.1109/TGRS.2020.2994349

Li, J., Wu, Z., Hu, Z., Jian, C., Luo, S., Mou, L., Zhu, X.X., Molinier, M.,
2021\. A Lightweight Deep Learning-Based Cloud Detection Method for Sentinel-2A
Imagery Fusing Multiscale Spectral and Spatial Features. IEEE Transactions on
Geoscience and Remote Sensing 1–19. https://doi.org/10.1109/TGRS.2021.3069641

Li, Y., Chen, W., Zhang, Y., Tao, C., Xiao, R., Tan, Y., 2020. Accurate cloud
detection in high-resolution remote sensing imagery by weakly supervised deep
learning. Remote Sensing of Environment 250.
https://doi.org/10.1016/j.rse.2020.112045

Li, Z., Shen, H., Cheng, Q., Liu, Y., You, S., He, Z., 2019. Deep learning based
cloud detection for medium and high resolution remote sensing images of
different sensors. ISPRS Journal of Photogrammetry and Remote Sensing 150,
197–212. https://doi.org/10.1016/j.isprsjprs.2019.02.017

Li, Z., Shen, H., Li, H., Xia, G., Gamba, P., Zhang, L., 2017. Multi-feature
combined cloud and cloud shadow detection in GaoFen-1 wide field of view
imagery. Remote Sensing of Environment 191, 342–358.
https://doi.org/10.1016/j.rse.2017.01.026

Lin, D., Xu, G., Wang, X., Wang, Y., Sun, X., Fu, K., 2019. A Remote Sensing
Image Dataset for Cloud Removal. arXiv preprint arXiv:1901.00600.

López-Puigdollers, D., Mateo-García, G., Gómez-Chova, L., 2021. Benchmarking
deep learning models for cloud detection in landsat-8 and sentinel-2 images.
Remote Sensing 13, 1–20. https://doi.org/10.3390/rs13050992

Main-Knorn, M., Pflug, B., Louis, J., Debaecker, V., Müller-Wilm, U., Gascon,
F., 2017. Sen2Cor for Sentinel-2, in: Bruzzone, L., Bovolo, F., Benediktsson,
J.A. (Eds.), Image and Signal Processing for Remote Sensing XXIII. SPIE, p. 3.
https://doi.org/10.1117/12.2278218

Mateo-García, G., Gómez-Chova, L., Amorós-López, J., Muñoz-Marí, J.,
Camps-Valls, G., 2018. Multitemporal cloud masking in the Google Earth Engine.
Remote Sensing 10, 7–9. https://doi.org/10.3390/rs10071079

Mateo-Garcia, G., Laparra, V., Lopez-Puigdollers, D., Gomez-Chova, L., 2020.
Cross-Sensor Adversarial Domain Adaptation of Landsat-8 and Proba-V Images for
Cloud Detection. IEEE Journal of Selected Topics in Applied Earth Observations
and Remote Sensing 14, 747–761. https://doi.org/10.1109/JSTARS.2020.3031741

Mohajerani, S., Saeedi, P., 2019. Cloud-Net: An End-To-End Cloud Detection
Algorithm for Landsat 8 Imagery, in: International Geoscience and Remote Sensing
Symposium (IGARSS). IEEE, pp. 1029–1032.
https://doi.org/10.1109/IGARSS.2019.8898776

Qiu, S., He, B., Zhu, Z., Liao, Z., Quan, X., 2017. Improving Fmask cloud and
cloud shadow detection in mountainous area for Landsats 4–8 images. Remote
Sensing of Environment 199, 107–119. https://doi.org/10.1016/j.rse.2017.07.002

Qiu, S., Zhu, Z., Woodcock, C.E., 2020. Cirrus clouds that adversely affect
Landsat 8 images: What are they and how to detect them? Remote Sensing of
Environment 246, 111884. https://doi.org/10.1016/j.rse.2020.111884

Scaramuzza, P.L., Bouchard, M.A., Dwyer, J.L., 2012. Development of the landsat
data continuity mission cloud-cover assessment algorithms. IEEE Transactions on
Geoscience and Remote Sensing 50, 1140–1154.
https://doi.org/10.1109/TGRS.2011.2164087

Shendryk, Y., Rist, Y., Ticehurst, C., Thorburn, P., 2019. Deep learning for
multi-modal classification of cloud, shadow and land cover scenes in PlanetScope
and Sentinel-2 imagery. ISPRS Journal of Photogrammetry and Remote Sensing 157,
124–136. https://doi.org/10.1016/j.isprsjprs.2019.08.018

Stillinger, T., Collar, N., 2019. Snow-Cloud Validation Masks for Multispectral
Satellite Data [Data set]. https://doi.org/10.5281/zennodo.3240937

Sun, H., Li, L., Xu, M., Li, Q., Huang, Z., 2020. Using Minimum Component and
CNN for Satellite Remote Sensing Image Cloud Detection. IEEE Geoscience and
Remote Sensing Letters 1–5. https://doi.org/10.1109/LGRS.2020.3014358

USGS., 2016a. L7 Irish Cloud Validation Masks. U.S. Geological Survey data
release.
https://landsat.usgs.gov/landsat-7-cloud-cover-assessment-validation-data.

USGS., 2016b. L8 Biome Cloud Validation Masks. U.S. Geological Survey, data
release.
https://landsat.usgs.gov/landsat-8-cloud-cover-assessment-validation-data.

USGS., 2016c. L8 SPARCS Cloud Validation Masks. U.S. Geological Survey data
release.
https://www.usgs.gov/core-science-systems/nli/landsat/spatial-procedures-automated-removal-cloud-and-shadow-sparcs.

Wu, X., Shi, Z., Zou, Z., 2021. A geographic information-driven method and a new
large scale dataset for remote sensing cloud/snow detection. ISPRS Journal of
Photogrammetry and Remote Sensing 174, 87–104.
https://doi.org/10.1016/j.isprsjprs.2021.01.023

Xie, F., Shi, M., Shi, Z., Yin, J., Zhao, D., 2017. Multilevel cloud detection
in remote sensing images based on deep learning. IEEE Journal of Selected Topics
in Applied Earth Observations and Remote Sensing 10, 3631–3640.
https://doi.org/10.1109/JSTARS.2017.2686488

Zhu, Z., Wang, S., Woodcock, C.E., 2015. Improvement and expansion of the Fmask
algorithm: Cloud, cloud shadow, and snow detection for Landsats 4-7, 8, and
Sentinel 2 images. Remote Sensing of Environment 159, 269–277.
https://doi.org/10.1016/j.rse.2014.12.014

Zhu, Z., Woodcock, C.E., 2014. Automated cloud, cloud shadow, and snow detection
in multitemporal Landsat data: An algorithm designed specifically for monitoring
land cover change. Remote Sensing of Environment 152, 217–234.
https://doi.org/10.1016/j.rse.2014.06.012

Zhu, Z., Woodcock, C.E., 2012. Object-based cloud and cloud shadow detection in
Landsat imagery. Remote Sensing of Environment 118, 83–94.
https://doi.org/10.1016/j.rse.2011.10.028

Zupanc, A., 2017. Improving cloud detection with machine learning.
https://medium.com/sentinel-hub/improving-cloud-detection-with-machine-learning-c09dc5d7cf13.

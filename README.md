# BioGPS
## [G](https://github.com/WHSmyself/BioGPS)enomic and [P](https://github.com/WHSmyself/BioGPS)henomic [S](https://github.com/WHSmyself/BioGPS)election <br>

## Brief introduction <br>
Genomic selection (GS) and phenomic selection (PS) are pivotal for accelerating plant breeding. However, the accuracy, robustness, and transferability of the two kinds of selection methods are underexplored, especially when addressing complex traits. In this study, we introduced a novel data fusion framework, termed GPS (Genomic and Phenomic Selection), aiming to improve predictive performance by integrating genomic and phenomic data using three kinds of fusion strategies: data fusion, feature fusion, and result fusion. Five widely used machine learning models (Lasso, RF, SVM, XGBoost, and LightGBM), and one advanced deep learning model (DNNGP) were selected and compared in the GPS framework.

## The flow chart of BioGPS <br>
![image](https://github.com/WHSmyself/BioGPS/blob/main/BioGPS.png)

## Version and download <br>
* [Version 0.1.0](https://github.com/WHSmyself/BioGPS/archive/refs/heads/main.zip) -First version released on October, 12th, 2024<br>

## INPUT
### Phenotype file
> `phenotype.txt`

| Phenotype1 | Phenotype2 | Phenotype3 | Phenotype4 | Phenotype5 | Phenotype6 | Phenotype7 | Phenotype8 | Phenotype9 |
| :---: | :---: |  :---: |  :---: |  :---: | :---: | :---: | :---: | :---: |
| 36 | 91.44 | 55.3 | 3718.93 | 6.62 | 31.43 | 20.84 | 4.9 | 7.9 |
| 33 | 83.82 | 45.9 | 3086.78 | 7.1 | 32.99 | 19.87 | 4.84 | 13.61 |
| 37 | 93.98 | 43.4 | 2918.65 | 7.07 | 32.34 | 20.77 | 4.84 | 13.04 |
| 41 | 104.14 | 51.8 | 3483.55 | 7.1 | 32.42 | 20.37 | 4.8 | 15.19 |
| 37 | 93.98 | 50.9 | 3423.03 | 7.27 | 31.03 | 20.57 | 4.96 | 13.24 |
| 38 | 96.52 | 49.5 | 3328.88 | 7.3 | 31.75 | 20.51 | 4.89 | 13.47 |

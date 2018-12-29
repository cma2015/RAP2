[![Docker Repository on Quay](https://quay.io/repository/bgruening/galaxy-rna-workbench/status "Docker Repository on Quay")](https://hub.docker.com/r/malab/tamf/)

## TAMF
- TAMF is designed to provide an easily accessible large-scale transcriptomic data analysis platform to help botanists even with little bioinformatics background completing complicated processing with terminal-based applications that are not user-friendly. It smoothly integrated the TAMF tools into Galaxy scientific analysis platform to provide web-based, easy-to-use and thoroughly tested tools enable users perfom comparative analysis. By integrating three major matrix factorization algorithmes (PCA [principle component analysis]; ICA [independent component analysis]; NMF [non-negative matrix factorization]), TAMF enables users perform a series of analysis based on pattern matrix (PM) and amplitude matrix (AM). For PM-based deep mining, four sub-modules are implemented to perform **Clustering analysis**, **single-cell analysis** (identify cell-types in single-cell RNA-Seq), **Spatial-course analysis** (illuminate the spatial dependency of sampled regions/voxels), and **Time-course analysis** (track the gene expression dynamics across temporal variations along the developmental stages); For AM-based deep mining, **Functional gene discovery** and **Pathway activity analysis** are provided to perform gene function prediction, gain biological insights into GWAS result, as well as active pathways, respectively. The TAMF project is hosted on GitHub (https://github.com/cma2015/TAMF) and can be accessed from http://bioinfo.nwafu.edu.cn:4002. In addition, in order to enable large-scale analysis, we also provided a standardized Docker image: [TAMF Docker image](https://hub.docker.com/r/malab/tamf/).

<img src="https://github.com/cma2015/TAMF/blob/master/TAMF_images/TAMF_workflow.jpg" alt="img" width = "80%" align="middle"/> 


## How to use CAFU

- More details about how to use CAFU are presented at https://github.com/cma2015/TAMF/blob/master/tutorial/TAMF-user-manual.md
- Test datasets can de downloaded from https://github.com/cma2015/TAMF/tree/master/test_data


## How to access help
* If users encounter any bugs or issues, feel free to leave a message at Github [issues](<https://github.com/cma2015/CAFU/issues>). We will try our best to deal with all issues as soon as possible.
* In addition, if any suggestions are available, feel free to contact: __Wenlong Ma__ <mawenlong_nwsuaf@163.com> or __Jingjing Zhai__ <zhaijingjing603@gmail.com> 



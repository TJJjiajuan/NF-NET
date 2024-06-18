# NF-NET
Design: We integrated datasets, comprising single cell RNA-seq data from 10 patients, single cell ATAC-seq data from 4 patients, and bulk RNA-seq data from 77 patients, to construct an integrated atlas encompassing both tumor and non-tumor cells within human NF-PanNETs tumor tissues. We then harnessed this atlas for follow-up analyses and experiments aimed at elucidating potential mechanisms underlying NF-PanNETs malignancy. The prognostic significance of our novel biomarker was validated in a cohort of 177 NF-PanNETs patients from two different institutions, all of whom lacked germline mutations.
Result: We have pinpointed a distinct subcluster of tumor cells, referred to as “atypical tumor cells”, responsible for driving the malignancy of NF-PanNETs. Within this subcluster, FOXM1 serves as a central transcription factor, orchestrating the transcriptional program that underlies the malignancy of NF-PanNETs. Additionally, we identified AGR2 as a novel prognostic marker. Patients with AGR2-positive NF-PanNETs exhibited several adverse prognostic factors, and as a result, experienced significantly poorer progression-free survival (PFS) and overall survival (OS). 

### Overview of NF-net
![alt
text](https://github.com/TJJjiajuan/NF-NET/blob/main/Doc/Main.png?raw=true).


## NF-NET
Here we show the results in the main figures
```

## Tutorials
We also give a small example of how to run STged. Here we use the simulated FISHplus data set as an example. There are two ways to run STged, (1) run STged step by step, (2) run the STged by a main function.
- [FISHplus with `STged`](https://github.com/TJJjiajuan/STged/blob/main/docs/Demo_STged_FISH.Rmd)
  
Please do not hesitate to contact Dr. Tu at tujiajuan@163.com
to seek any clarifications regarding any content or operation of the
archive.

**# STged
R package supporting the paper **"STged: Gene expression deconvolution for spatial transcriptomic data"**. 

STged integrates spatial correlation patterns of gene expression and intra-cell type expression similarity to achieve precise and robust deconvolution results. Implemented within a non-negative least-squares regression framework, STged models gene expression levels at each spot as a weighted linear combination of cell type-specific gene expression, with the weights corresponding to the respective cell type proportions. By incorporating a spatial neighborhood graph prior, STged captures spatial correlation structures in cell type expressions across spots. Moreover, it integrates cell type-specific gene expression information prior from scRNA-seq data to enhance accuracy.
### Overview of STged
![alt

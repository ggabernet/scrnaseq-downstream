# single-cell RNAseq analysis for liver biology

Data analysis scripts for the scRNAseq data after processing with the cellranger pipeline.

The Rmarkdown notebooks are published at [https://ggabernet.github.io/scrnaseq-downstream/](https://ggabernet.github.io/scrnaseq-downstream/).

These project results were published in the article:

> Downregulation of TGR5 (GPBAR1) in biliary epithelial cells contributes to the pathogenesis of sclerosing cholangitis.
>
> Reich M, Spomer L, Klindt C, Fuchs K, Stindt J, Deutschmann K, Höhne J, Liaskou E, Hov JR, Karlsen TH, Beuers U, Verheij J, Ferreira-Gonzalez S, Hirschfield G, Forbes SJ, Schramm C, Esposito I, Nierhoff D, Fickert P, Fuchs CD, Trauner M, García-Beccaria M, Gabernet G, Nahnsen S, Mallm JP, Vogel M, Schoonjans K, Lautwein T, Köhrer K, Häussinger D, Luedde T, Heikenwalder M, Keitel V.
>
> _J Hepatol._ 2021 Apr 16:S0168-8278(21)00244-0.
> doi: 10.1016/j.jhep.2021.03.029. Epub ahead of print. PMID: 33872692.

## MDR2 KO vs WT experiment

Single-cell RNAseq data analysis, using the Seurat package, of extracted liver cells from wild-type mice and mice with a MDR2 gene knock-out. Contains conda environment `environment.yml` used for the analysis and Rmarkdown scripts.

## TGR5 TG vs MDR2 KO experiment

Single-cell RNAseq data analysis, using the Seurat package, of extracted liver cells from mice with a MDR2 gene knock-out and mice additionally with a TGR5 transgene overexpression. Contains conda environment `environment.yml` used for the analysis and Rmarkdown scripts.

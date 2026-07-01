# single-cell RNA-seq analysis

Relevant scripts

## Getting Started

Processing of raw data (fastq) was done in CellRanger to generate the .mtx files which were then imported in Seurat package for downstream processing. For more on versions of the softwares/ genome/ transcriptome annotation used, please refer to the pre-print. Scripts here involve -
* Seurat based processing of in-house scRNA
* Python notebook to extract colonic epithelial cell type based gene signatures from the GutCellAtlas data
* And, application of above cell type signatures on in-house scRNA to annotate UMAP clusters

Python notebooks were executed in Google Colab.

### Prerequisites

Relevant R/ python packages are indicated in the beginning of the scripts by 'library' or 'import' calls respectively.

### Installing

Guidelines on installing R packages can be found here -
* https://cran.r-project.org/doc/manuals/r-patched/R-admin.html
* https://www.bioconductor.org/install/

Introduction to using Colab based python notebooks can be found here -
* https://colab.research.google.com/notebooks/basic_features_overview.ipynb
* https://colab.research.google.com/notebooks/snippets/importing_libraries.ipynb


## Authors

* **Amit Mandal**


## License

This project is licensed under the GNU GPLv3 License.

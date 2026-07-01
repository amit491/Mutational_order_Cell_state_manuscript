# bulk RNA-seq analysis

Relevant scripts

## Getting Started

Processing of raw data (fastq) went through usual steps of fastq quality-checks, and then alignment to genome+transcriptome using STAR. For more on versions of the softwares/ genome/ transcriptome annotation used, please refer to the pre-print. Scripts here involve the downstream processing of the gene counts (STAR output).

### Prerequisites

STAR count data was analysed in R using packages available in CRAN/ BioConductor repositories. Relevant packages are mentioned in the scripts -

```
library(my_pkg)
```

### Installing

Guidelines on installing R packages can be found here -
* https://cran.r-project.org/doc/manuals/r-patched/R-admin.html
* https://www.bioconductor.org/install/


## Authors

* **Amit Mandal**


## License

This project is licensed under the GNU GPLv3 License.

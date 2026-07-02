# bulk ATAC-seq analysis

Relevant scripts

## Getting Started

Processing of raw data (fastq) to create BAMs and subsequently tagAlign (TA) files were done as per ENCODE ATAC-seq guidelines which are found on this page -
* https://github.com/encode-dcc/atac-seq-pipeline , or direct link to the pipeline steps here -
* https://docs.google.com/document/d/1f0Cm4vRyDQDu0bMehHD7P7KOMxTOP-HiNoIvL1VcBt8/edit?usp=sharing

Some differences adopted were -
* Mapping quality threshold for filtering BAM was kept at '1', rather than '30', to retain more reads.
* MACS v3 was used, rather than v2

More details on the steps are in the Methods section of the pre-print.

The scripts here are the post-processing of the peak calling output using R -
* De-novo motif scan
* Genomic context annotation of peaks
* Per-gene ATAC score calculation and plotting
* AP-1 motif accessibility quantification, and plotting

### Prerequisites

Relevant R python packages are indicated in the beginning of the scripts by 'library' calls.

### Installing

Guidelines on installing R packages can be found here -
* https://cran.r-project.org/doc/manuals/r-patched/R-admin.html
* https://www.bioconductor.org/install/


## Authors

* **Amit Mandal**


## License

This project is licensed under the GNU GPLv3 License.

# Using GutAtlas to extract colonic epithelial cell type specific signatures

Relevant python notebooks

## Getting Started

The raw counts for the "Space-Time Gut Cell Atlas" were downloaded by going here -
* https://www.gutcellatlas.org/
and then expanding the drop-down menu for the above mentioned data, and downloading the 'Raw H5AD Data':
* epi_raw_counts02_v2.h5ad

The file was then processed using scanpy/ scverse packages on Google Colab

### Prerequisites

scanpy/ scverse packages in local python notebook or Colab.

### Installing

Packages within python notebook can be insalled using 'pip'.
Each notebook starts with installation steps for the required packages.

### Legend for the notebooks -
First colonic epithelial (healthy) cells from the Gut Cell Atlas dataset mentioned above were pseudo-bulked ('pB') using large bowel specific cells ('LBowel' set).
Some cell types like Paneth and EEC didn't have enough replicates left after pB, and hence for those small intestine cells were also included ('Gut' set).

* **pseudoBulk_Lbowel.ipynb** - Pseudo-bulking the large bowel specific cells
* **pseudoBulk_Gut.ipynb** - Pseudo-bulking with the small intestine cells included as well
* **pb_dat_DESeq_02Apr2026.ipynb** - Using DESeq to extract signatures for cells: TA, Colonocytes, Stem & Goblet, from the 'LBowel' pB
* **pB_dat_DESeq_23Apr2026.ipynb** - Same as above, but for BEST2+ve Goblet and BEST4+ve Epi. cells.
* **pb_dat_DESeq_13Apr2026.ipynb** - Using DESeq to extract signatures for cells: Paneth & EEC, from the 'Gut' pB

## Authors

* **Amit Mandal**


## License

This project is licensed under the GNU GPLv3 License.

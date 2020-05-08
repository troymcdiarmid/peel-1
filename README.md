
# McDiarmid-etal-2020_peel-1-DMS-analysis

Analysis code for "Peel-1 negative selection promotes screening-free CRISPR-Cas9 genome editing in Caenorhabditis elegans. " (DOI: 10.1101/687194)

<!-- TABLE OF CONTENTS -->
## Table of Contents
* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
  * [Data](#data)
* [Contact](#contact)
* [Project authors](#project-authors)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

* Preprint (BioRxiv): [https://doi.org/10.1101/687194](https://doi.org/10.1101/687194)
* Data repository (Dataverse): [https://doi.org/10.5683/SP2/FJWIL8](https://doi.org/10.5683/SP2/FJWIL8)
* Analysis source code repository (Github): [https://github.com/troymcdiarmid/peel-1](https://github.com/troymcdiarmid/peel-1)

>SUMMARY:  
>Improved genome engineering methods that enable automation of large and precise edits are essential for systematic investigations of genome function. We adapted peel-1 negative selection to an optimized Dual-Marker Selection (DMS) cassette protocol for CRISPR-Cas9 genome engineering in Caenorhabditis elegans and observed robust increases in multiple measures of efficiency that were consistent across injectors and four genomic loci. The use of Peel-1-DMS selection killed animals harboring transgenes as extrachromosomal arrays and spared genome edited integrants, often circumventing the need for visual screening to identify genome edited animals. To demonstrate the applicability of the approach, we created deletion alleles in the putative proteasomal subunit pbs-1 and the uncharacterized gene K04F10.3 and used machine vision to automatically characterize their phenotypic profiles, revealing homozygous essential and heterozygous behavioral phenotypes. These results provide a robust and scalable approach to rapidly generate and phenotype genome edited animals without the need for screening or scoring by eye.

Please see the pre-print for more information about the project.


<!-- GETTING STARTED -->
## Getting Started

Make sure that you have R installed with the requirements listed below. Raw and processed data can be obtained from the Dataverse link mentionned above.

### Prerequisites
The code was executed using the following R version and platform:
```
R version 4.0.0 (2020-04-24) -- "Arbor Day"
Copyright (C) 2020 The R Foundation for Statistical Computing
Platform: x86_64-apple-darwin17.0 (64-bit)
```

### Installation
The R packages required for this project are listed at the beginning of the `peel1_analysis_markdown`. There may be additional system packages that need to be installed outside of the R environment.

Please report any missing dependencies/requirements by [opening an issue](https://github.com/troymcdiarmid/peel-1/issues) on this repository.

### Data
Raw or preprocessed data can be obtained from our lab dataverse.


<!-- LICENSE -->
<!--
## License

Distributed under the *** License. See `LICENSE` for more information.
-->


<!-- CONTACT -->
## Contact
For questions or comments specific to the implementation provided in this repository, please contact:

Troy A. McDiarmid - [GitHub](https://github.com/troymcdiarmid) - [@Troy_McD_UBC](https://twitter.com/Troy_McD_UBC)

Additional questions about the project, such as further information and requests for resources and reagents should be directed to and will be fulfilled by the Lead Contact, Catharine H. Rankin (crankin@psych.ubc.ca).

<!-- PROJECT AUTHORS -->
## Project authors
* Troy A. McDiarmid  
* Vinci Au
* Donald G. Moerman
* Catharine H. Rankin

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
We would like to thank Dr. John Calarco, Dr. Christian Frøkjær-Jensen, Dr. Geraldine Seydoux, Dr. Erik Jorgensen, and their labs for sharing constructs, reagents, and protocols or making them available. We would also like to thank members of the Rankin and Moerman labs for helpful discussions about the project. This work was supported by a Canadian Institutes of Health Research (CIHR) Doctoral Research Award to TAM, and a CIHR project grant (grant #CIHR MOP 130287) to CHR.
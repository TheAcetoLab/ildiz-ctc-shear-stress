# Synthetic lethality with shear stress: exploiting hemodynamic forces 
to dismantle circulating tumor cells


A [workflowr][] project.

[workflowr]: https://github.com/workflowr/workflowr




## Data pre-processing

Raw data is available at Gene Expression Omnibus (GEO, NCBI; accession numbers [GSE285703](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE285703),  [GSE285704](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE285704) and [GSE285711](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE285711) ). Data processing is computationally expensive and is not covered in this repository. We provide description of the data pre-processing workflow together with software version in the original publication. Processed data and large result files are  archived at [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14600505.svg)](https://doi.org/10.5281/zenodo.14600505).


##  Data and code availability

To reproduce our analysis, first clone source code from the [GitHub repository](https://github.com/TheAcetoLab/ildiz-ctc-shear-stress). This repository is also archived at [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXXXXX.svg)](https://doi.org/10.5281/XXXXXXXXXX)

    git clone https://github.com/TheAcetoLab/saini-stealTHY

Next, download processed data and output data deposited in [Zenodo](https://doi.org/10.5281/zenodo.14600505) into the cloned project folder and untar the files.

    for file in *.tar.gz; do tar xzvf "${file}" && rm "${file}"; done

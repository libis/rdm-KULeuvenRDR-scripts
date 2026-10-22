# DownloadDataset
The provided python script helps you download a specified version of a dataset from KU Leuven RDR, keeping the directory structure. 

## Instructions on how to use the python script
Usage (in command line):

``` Bash
python download_dataset.py --host https://rdr.kuleuven.be/ --dataset doi:authority/identifier --version version_no
```

### Arguments: 
`-o --output`: The output directory. If not specified, a default directory based on dataset doi and version will be used (current_dir/datasets/doi/version/)

`--host`: https://rdr.kuleuven.be/ (required)

`--dataset`: dataset DOI in the format of  doi:......../...... or https://doi.org/......../...... (required)

`--version`: dataset version number (required)
    
Gives a short report after download finishes with the number of correctly downloaded, already present, failed, and restricted files, as well as a detailed log file with the filenames.

### Acknowledgement
This script was based on previous work done and shared by [Jonathan Dan](https://people.epfl.ch/jonathan.dan/?lang=en) from EPFL.


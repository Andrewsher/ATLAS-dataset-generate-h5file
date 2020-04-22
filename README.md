# README

Generate h5 file for [ATLAS Dataset](https://www.nature.com/articles/sdata201811).
H5 file which contains this dataset will be created under current directory. 
The generated h5 file will contain 2 arrays, each contains 43281 slices.
The value range of image will be converted to [0,1].

Requirements:

 * nibabel
 * tqdm
 * h5py

Usage:

``` bash
python generate_h5.py --data-path ${ATLAS_DATASET_PATH}$
```
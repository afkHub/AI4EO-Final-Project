# AI4EO-Final-Project
This project aims to monitor sea ice and detect different sea ice types using satellite SAR data in the North Atlantic region. The scripts were written for the final report of the *"AI4EO Platforms and Best Practices"* course given by @adamjstewart at TUM.

## Data Acquisition

The project utilizes satellite data and other datasets, which need to be downloaded separately as they are not included in the repository.

### Satellite Data:

1. **Sentinel-1 Data:**
   - The data file `S1A_EW_GRDM_1SDH_20240405T211859_20240405T211959_053304_067647_844B.SAFE.zip` can be accessed by searching for this name in the [Copernicus Open Access Hub](https://browser.dataspace.copernicus.eu/).

   - For the midterm, the free ICEYE data used can be downloaded from [this link](https://www.iceye.com/lp/example-scan-dataset-hudson-strait).
   - Another Sentinel-1 data file used for the midterm, `S1A_EW_GRDM_1SDH_20220213T115657_20220213T115757_041894_04FCE8_A2D1.SAFE.zip`, can also be accessed through the Copernicus browser as mentioned above.

### SAR Data Pre-Processing:

- For pre-processing SAR data, the SNAP software is used. You can download it from [this link](https://step.esa.int/main/download/snap-download/).

### Deep Learning Training Dataset:

- The dataset named **SI-STSAR-7** is required to train the DL models. You can download it from [this link](https://ieee-dataport.org/open-access/si-stsar-7). Only the `.zip` and `.txt` files are needed.
- After downloading the `.zip` files, extract the `.npy` files and keep them in the same directory.

## Required Libraries

The following libraries are required to run the scripts in this project repository:

- **NumPy**: `numpy`
- **TIFFFile**: `tifffile`
- **OS Module**: `os`
- **Rasterio**: `rasterio`
- **Scikit-Learn**: `scikit-learn`
- **Matplotlib**: `matplotlib`
- **Warnings Module**: `warnings`
- **Torch**: `torch`
- **TorchVision**: `torchvision`
- **PIL (Pillow)**: `Pillow`
- **TQDM**: `tqdm`
- **TensorFlow**: `tensorflow`
- **Time Module**: `time`
- **Matplotlib.colors**: `matplotlib.colors`


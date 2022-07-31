# Explorations in visualizing zarr

## Generate ndpyramids

First, generate an ndpyramid for the dataset of interest. The ndpyramid acts as overviews for the underlying Zarr store.

```bash
conda install nb_conda_kernels
conda create --name zarr-viz
conda activate zarr-viz
conda install pip ipykernel
pip install -r requirements.txt
conda install -c conda-forge rasterio
conda deactivate
jupyter notebook
```

The current example in smap.ipynb generates an ndpyramid from an SMAP L3 Soil Moisture dataset.

## Run the server

```bash
nvm use 
npm i
npm run dev
```

## Deployment

Deploy has been automated with AWS Amplify Hosting: https://main.d2u6db8f1m88nx.amplifyapp.com/



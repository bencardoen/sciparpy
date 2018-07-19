### Install Miniconda3
```bash
wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
chmod u+x Miniconda3-latest-Linux-x86_64.sh
./Miniconda3-latest-Linux-x86_64.sh
```
### Install dependencies
```bash
$conda install numba
$conda install -c condaforge zarr
$conda install dask pyarrow numpy jupyter numba cffi git bokeh joblib line_profiler memory_profiler snakeviz matplotlib cython vtk scikit-learn scipy
$pip install contexttimer
```
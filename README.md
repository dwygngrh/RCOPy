# RCOPy
Some python code for oceanographic data processing in RCO-BRIN

## Miniconda installation under linux using Python39
<p>Open Powershell in windows

wget "https://repo.anaconda.com/miniconda/Miniconda3-py39_24.11.1-0-Windows-x86_64.exe" -outfile "./Downloads/Miniconda3-python39-Windows-x86_64.exe"</p>

cd Downloads

./Miniconda3-python39-Windows-x86_64.exe 

cd ..

after installation is finished, select Anaconda prompt in start menu windows

you will enter the anaconda prompt 

## Create new conda environment name = ocean python39

conda create --name ocean python=3.9

conda activate ocean

## Installing some libraries in anaconda prompt

conda install conda-forge::numpy

conda install conda-forge::scipy

conda install conda-forge::matplotlib

conda install conda-forge::basemap

conda install conda-forge::netcdf4

conda install anaconda::pandas

conda install conda-forge::plotly

conda install anaconda::seaborn

conda install anaconda::pywavelets

conda install jupyter

## Menggunakan Jupyter Notebook untuk Python Programming

Create a new directory

mkdir python_training

cd python_training

jupyter notebook

Copy the URL's to your browser

Now You have a jupyter notebook opened in your browser

## test case Banda surface data 1 Jan 2022 - 31 Dec 2024

python baca data text banyak kolom dengan kolom pertama tanggal dan plot masing masing kolom dengan xaxis adalah tanggal per bulan lalu buat moving average dan selanjutnya buat korelasi pada tiap variabel menggunakan heatmap dan PCA selanjutnya buat candle stick rata rata bulanan selanjutnya buat Empirical orthogonal function selanjutnya buat power spectrum density














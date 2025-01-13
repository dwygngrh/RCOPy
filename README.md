# RCOPy
Some python code for oceanographic data processing in RCO-BRIN

## Miniconda installation under Windows using Python39 (worked well in windows 11)
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

conda install conda-forge::gsw

conda install jupyter

## Menggunakan Jupyter Notebook untuk Python Programming

Create a new directory

mkdir python_training

cd python_training

jupyter notebook

Copy the URL's to your browser

Now You have a jupyter notebook opened in your browser

## Silahkan Download data di Github ini

### buka data di notepad dan pelajari isi data tersebut

data_banda.txt

TS_halmahera.txt

# latihan menggunakan Python

## test case Banda surface data 1 Jan 2022 - 31 Dec 2024

### berikan perintah berikut ke chat GPT

kode python baca data text banyak kolom dengan kolom pertama tanggal dan plot masing masing kolom dengan xaxis adalah tanggal per bulan lalu buat moving average dan selanjutnya buat korelasi pada tiap variabel menggunakan heatmap dan PCA selanjutnya  buat power spectrum density selanjutnya buat continous wavelet transform

SIlahkan coba untuk prediksi menggunakan machine learning (random forest atau arima)

## test case TS diagram Halmahera sea

### berikan perintah berikut ke chat GPT

buat code python bagaimana membuat TS diagram dengan data dari file text dan kontur densitas TEOS-10 menggunakan kontur dash line dan kontur label














# RCOPy
Some python code for oceanographic data processing in RCO-BRIN

## Miniconda installation under linux using Python39

Open Powershell in windows

wget "https://repo.anaconda.com/miniconda/Miniconda3-py39_24.11.1-0-Windows-x86_64.exe" -outfile "./Downloads/Miniconda3-python39-Windows-x86_64.exe"

cd Downloads

./Miniconda3-python39-Windows-x86_64.exe 

after installation is finished, select Anaconda prompt in start menu windows

you will enter the anaconda prompt 

## Create new conda environment name = ocean python39

conda create --name ocean python=3.9

conda activate ocean

## Installing some libraries in anaconda prompt

conda install conda-forge::numpy

conda install conda-forge::scipy

conda install conda-forge::matplotlib

conda install conda-forge::netcdf4

conda install conda-forge::basemap

conda install jupyter









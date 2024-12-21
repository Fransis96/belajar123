# Integrasi Spark dengan Jupyter Notebook  
<i>by: ffrancezt</i>  
<br>

### Instalasi Jupyter Notebook

1. Update dan upgrade sistem:  
```bash 
sudo apt update && sudo apt upgrade -y  
```
2. Untuk tahapan instalasi sistem operasi anda harus sudah terinstall aplikasi python 
3. Gunakan perintah dibawah ini untuk proses instalasi
```bash
sudo apt install python3  
```
4. Kemudian install python3-pip dengan perintah:
```bash
sudo apt install python3-pip  
```
5. Buat direktori jupyter dan masuk kedalam direktori tersebut dengan perintah: 
```bash
mkdir jupyter && cd jupyter  
```
6. Install Virtual environment untuk Python 3  
```bash
sudo apt install python3-virtualenv   
```
7. Buat virtual environment baru dengan nama jup_notebook
```bash
virtualenv jup_notebook  
```
8. Aktifkan virtual environment  
```bash
source jup_notebook/bin/activate  
```
9. Perbarui pip (python package manager) ke versi terbaru  
```bash
pip3 install --upgrade pip  
```
10. Install Virtualenv menggunakan pip3  
```bash
pip3 install virtualenv  
```
11. Instal Jupyter Notebook menggunakan pip3  
```bash
pip3 install notebook  
```
12. Instal Jupyter Core dan Jupyter Notebook melalui paket sistem berbasis Ubuntu.  
```bash
sudo apt install jupyter-core jupyter-notebook  
```
13. Setelah selesai instalasi, kita perlu melakukan beberapa tahapan konfigurasi. Untuk membuat file konfigurasi dari jupyter notebook, gunakan perintah:  
bash```
jupyter-notebook --generate-config
```
14. Buka file konfigurasi Jupyter Notebook menggunakan text editor nano  
```bash
nano /home/ubuntu/.jupyter/jupyter_notebook_config.py  
```
Kemudian Masukan:
```bash
c.NotebookApp.ip = '0.0.0.0'
c.NotebookApp.port = 8889
c.NotebookApp.open_browser = False
c.NotebookApp.allow_root = True
```
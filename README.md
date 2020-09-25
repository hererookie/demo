_**web service deploy deeplearning model**_
model+deploy 
apache2
flask
redis

pip3安装的:

tensorflow-gpu==1.12
keras==2.2.4
h5py

matplotlib
pillow
sklearn
easydict

urllib3
pyopenssl
ndg-httpsclient
pyasn1
pymongo

faiss

sqlalchemy
pymysql
pyodbc


apt-get 安装的：

libopenblas-dev
libomp-dev
msodbcsql17
unixodbc-dev

############################################
注：安装msodbcsql17时，安装方法可参考：

apt-get update -y && apt-get install curl -y
curl https://packages.microsoft.com/keys/microsoft.asc | sudo apt-key add -
echo "deb [arch=amd64] https://packages.microsoft.com/ubuntu/18.04/prod bionic main" | sudo tee /etc/apt/sources.list.d/mssql-release.list
sudo apt update
sudo apt install msodbcsql17

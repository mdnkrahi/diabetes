```sudo su```

```sudo apt update -y```

```sudo apt-get install libgl1-mesa-dev -y```

curl -O https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh -b
rm -r Miniconda3-latest-Linux-x86_64.sh
source /root/miniconda3/bin/activate
conda create -n diabetes python=3.9.13
conda activate diabetes 

git clone https://github.com/mdnkrahi/diabetes.git
cd diabetes

pip install -r requirements.txt
flask run

```ssh -i "/c/Users/Nadeem Khan/key.pem" -N -L 5000:localhost:5000 ubuntu@54.174.219.169```

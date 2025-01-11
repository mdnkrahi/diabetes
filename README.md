```sh
sudo su
```

```sh
sudo apt update -y
```

```sh 
sudo apt-get install libgl1-mesa-dev -y
```

```sh 
curl -O https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
```


```sh
bash Miniconda3-latest-Linux-x86_64.sh -b
```


```sh
rm -r Miniconda3-latest-Linux-x86_64.sh
```


```sh
source /root/miniconda3/bin/activate
```


```sh
conda create -n diabetes python=3.9.13
```


```sh
conda activate diabetes
 ```


```sh
git clone https://github.com/mdnkrahi/diabetes.git
```


```sh
cd diabetes
```

```sh 
pip install -r requirements.txt
```


```sh
flask run
```



```sh 
ssh -i "/c/Users/Nadeem Khan/key.pem" -N -L 5000:localhost:5000 ubuntu@54.174.219.169
```

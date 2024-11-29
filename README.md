# TDDRL - (Twin DDPG Algorithm) Python code
Research Paper : https://ieeexplore.ieee.org/document/9434412

Steps for running the code in google collab:
```shell
from google.colab import drive
drive.mount('/content/drive')

%cd /content/drive/MyDrive/Twin-DDPG-Python

!pip install -r requirements.txt

!python main_test.py
```


The `main_test.py` is the main running python file. To run it in the `bash` or `powershell`, please type 

```shell
conda create --name myenv python=3.10.4
conda activate myenv
pip install -r requirements.txt
python main_test.py
```

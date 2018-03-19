# WebAnsi-API
The project is a web interface written in python, that can configure devices both using ansible and API calls.

## Requirements:
- Python 3.6
- Pip
### Pip:
- requests==2.12.4
- Flask==0.12.2
- ncclient==0.5.3
- ansible==2.4.2.0

## Instalation:
```
mkdir git
cd git
git clone https://github.com/Helweg/WebAnsi-API.git
cd WebAnsi-API
pip install -r requirements.txt --no-index
```

## Add devices:
Open the 'hosts' file and add the device IP to All.


## Usage:
```
Python3 Web.py
```
Access the webpage at:
```
127.0.0.1:5000
```

####  참고  다음의 영상을 보고 따라해봄.  링크 https://www.youtube.com/watch?v=xqroBkpf3lY&t=74s


#### orin_yolov8 준비물
orin 4gb, realsence camera, yolov8
#### chapter 1.
##### 1. pip는 Python 패키지를 설치하고 관리하는 데 필수적인 도구
``` bash
 sudo apt install python3-pip 
```
##### 2. Python의 패키지 관리 도구인 pip를 사용하여 python-dateutil 패키지를 설치하거나 업데이트하는 데 사용, python-dateutil 패키지는 Python에서 날짜와 시간을 다루는 데 유용한 확장 기능을 제공
``` bash
pip3 install -U python-dateutil
```
##### 3. ultralytics 패키지를 설치
``` bash
pip3 install ultralytics
```
##### 결과 결과
 Successfully installed filelock-3.13.1 fsspec-2024.2.0 jinja2-3.1.3 networkx-3.2.1 numpy-1.26.4 opencv-python-4.9.0.80 psutil-5.9.8 py-cpuinfo-9.0.0 seaborn-0.13.2 thop-0.1.1.post2209072238 torch-2.2.0 torchvision-0.17.0 tqdm-4.66.1 typing-extensions-4.9.0 ultralytics-8.1.10

torch-2.2.0 torchvision-0.17.0
##### 4~5. uninstall 영상에는 있으나 나는 skip

``` bash
pip3 uninstall torch
pip3 uninstall torchvision
```

#### chapter 2. Prerequisites and Installation
##### 2-2. Install system packages required by PyTorch:

```` bash
 sudo apt-get -y update; 
 sudo apt-get -y python3-pip libopenblas-dev;


##### Next, install PyTorch with the following steps:
Export with the following command:



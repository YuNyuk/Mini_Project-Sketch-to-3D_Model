## Team members

1. 김정대
2. 권오준
3. 이윤혁

## Purpose

떠오르는 아이디어가 있지만 도면이나 그림으로 바로 나타내기 어려운 사람이 손쉽게 모델링하여 확인할 수 있도록 함

## High Level Design

- 스케치한 도면과 키워드를 입력
    - 도면과 키워드에 따라 새로운 이미지 생성
- 생성된 이미지를 객체만 추출하여 3D 모델링
- 추가로 음악 키워드 입력시 원하는 분위기에 맞는 BGM 생성

![Screenshot from 2024-07-01 09-27-52](https://github.com/kccistc/intel-04/assets/142381053/a331a837-d523-4f02-b571-c995c8fcb688)


## Github link

https://github.com/jd6286/SH2GH

## Prerequite

```python
python3 -m venv sh2gh
source sh2gh/bin/activate
git clone https://github.com/GaParmar/img2img-turbo.git
# Install requirements
pip3 install -U pip
pip3 install -r requirements.txt --extra-index-url https://download.pytorch.org/whl/cpu
```

## Model Excute

```python
python main.py
```

## Result
- GUI
  
![Screenshot from 2024-07-01 09-30-42](https://github.com/kccistc/intel-04/assets/142381053/039f7de3-c38c-45ff-8537-d209d559b2dd)

- 원본 이미지
  
![Screenshot from 2024-07-01 09-31-52](https://github.com/kccistc/intel-04/assets/142381053/7b9ab3ce-9af8-4365-8f7e-9488bc2767f7)

- 3D 이미지
  
![Screenshot from 2024-07-01 09-32-28](https://github.com/kccistc/intel-04/assets/142381053/d3af1359-d485-4fa0-9b0d-d82ec636885e)


## Demo

https://drive.google.com/file/d/12uHbnKXtz3ksCBNqbf-WtNpigkmD6zYF/view


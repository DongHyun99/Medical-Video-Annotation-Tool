# Info-Maker

## 개요

```헬스허브```와의 산학 프로젝트 일환으로 DICOM Annotation Tool 개발을 위한 Repo이다.  

## 목표

기업에서 제공한 목표는 총 4가지이다.  

### 조사
- [x] DICOM 이란 무엇일까? 개인정보보호는 무엇이고 어떻게 해야 할까? (조사 및 발표)

### 프로그램 개발
- [ ] DICOM 비식별화 프로그램 만들기 (프로그램)
- [ ] DICOM 영상을 읽고 점, 사각형, 자유영역 그리기 + 레이블링 (프로그램)
- [ ] 점, 사각형, 자유영역과 레이블을 json 형태로 추출하기 (프로그램)  

## 기대효과

- AI가 흉부 질병을 진단하는 데 필요한 정보들을 학습 목적에 맞도록 사용자가 자유롭게 추가할 수 있다.  
- 손쉬운 Labeling Tool 개발을 통해 높은 생산성으로 양질의 자료를 생산해낼 수 있도록 돕는다.  
- DICOM에 대해 명확히 앎으로써 프로젝트에서 다른 이미지 매체가 아닌 DICOM의 필요성을 알 수 있다.  
- 의료 정보(개인정보)유출로 발생하는 문제점을 파악하고 정보보호를 위한 대책을 마련할 수 있다.
- DICOM을 통해 알 수 있는 개인정보는 무엇인지, 그리고 이를 보호하기 위해 어떤 방식을 써야 할지 알 수 있게 된다.  

## 개발일지

추후 추가 예정

## Installation
/* Please use commend "pip install -r requirements.txt" before execute this program.*/

```
imgviz==1.2.6
numpy==1.19.5
pillow==8.3.1
PyQt5==5.15.2
PyQt5-sip==12.9.0
QtPy==1.9.0
scikit-image==0.17.2
scipy==1.5.4
matplotlib==3.2.2
opencv-python==4.5.3.56 
termcolor==1.1.0
colorama==0.4.4
```
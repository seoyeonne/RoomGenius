<h1>
  <img src="https://github.com/user-attachments/assets/54e33ebc-a2e8-4c5c-bcbe-5884f31c970e" alt="Logo" width="30">
  RoomGenius
</h1>


## 📑 Content

1. [🏡 AI 기반 개인 맞춤형 인테리어 디자인 플랫폼](#-ai-기반-개인-맞춤형-인테리어-디자인-플랫폼)
2. [📖 About](#-about)
3. [🛠 Features](#-features)
4. [🎥 Demo](#-demo)
5. [👥 Team](#-team)
6. [👨‍🏫 Coach](#-coach)
7. [⚙ Install](#-install)
8. [📋 Requirements](#-requirements)
   
## 🏡 AI 기반 개인 맞춤형 인테리어 디자인 플랫폼 

해당 프로젝트는 2024학년도 1학기 캡스톤 디자인 프로젝트 입니다.


https://github.com/user-attachments/assets/acbcb6ce-a6dc-4879-bd1b-96509d83c9ba


최근 사람들의 개성과 취향을 반영한 맞춤형 공간 설계에 대한 관심이 꾸준히 늘어나고 있습니다. 특히 인테리어에 대한 열풍이 불면서, 많은이들이 자신의 공간을 직접 꾸미고 디자인하려는시도를 하고 있습니다. 그러나 디자인 경험이 부족한 사람들에게는 가구 배치나 색상 조합 같은 과정이 어렵게 느껴지기 마련입니다. 전문가의 도움을 받을 수도 있지만, 이는 시간과 비용 부담이 커서
선뜻 시도하기 어려운 경우가 많습니다. 이러한 이유로, 누구나 간편하게 자신의 취향을 반영한 인테리어를 계획할 수 있는 도구의 필요성이 증가하고 있습니다.

## 📖 About
RoomGenius는 AI를 활용하여 개인 맞춤형 인테리어를 제공하는 플랫폼입니다.
텍스트 입력과 이미지를 업로드하면, AI가 공간의 특성을 분석하고 디자인 스타일에 맞는 인테리어 이미지를 생성합니다.

## 🛠 Features
	•	텍스트 기반 인테리어 이미지 생성: 사용자가 제공한 텍스트 프롬프트에 맞는 공간 이미지를 생성합니다.
	•	이미지 기반 인테리어 추천: 업로드된 이미지의 특성을 분석하고, 사용자의 스타일에 맞는 공간 설계를 제안합니다.
	•	가구 및 소품 추천: 생성된 디자인에 적합한 IKEA 가구와 소품 정보를 제공하여 현실적인 구매를 돕습니다.
	•	번역 및 다국어 지원: 텍스트를 자동으로 영어로 번역하여 글로벌 사용자를 지원합니다.

## 🎥 Demo
- img와 프롬프트를 통한 방 이미지 생성
프롬프트 : 따뜻한 붉은색 벽난로와 어두운 회색 러그로 꾸며진 크리스마스 트리와 금색 장식의 인테리어(아랍어)

https://github.com/user-attachments/assets/c5ff8baf-8d9d-416d-94fe-123eb0fe0c17

<table align="center">
  <tr>
    <td align="center">
      <img width="203" alt="이미지투결과" src="https://github.com/user-attachments/assets/7a50e314-50fa-4c5d-a4c8-ba141ee8421e">
      <br>
      <strong>이미지 결과</strong>
    </td>
    <td align="center">
      <img width="203" src="https://github.com/user-attachments/assets/7a0c1d5f-3aa8-4082-933f-e8edbc084854" alt="이미지투원본">
      <br>
      <strong>이미지 원본</strong>
    </td>
  </tr>
</table>
  
- text를 이용한 방 이미지 생성
프롬프트 : 스타워즈 테마의 침실, 어두운 우주 배경 벽지와 LED 조명이 설치된 인테리어

https://github.com/user-attachments/assets/49c766fe-b80a-49f3-b214-8b82378ddca8

- Sketch된 이미지와 프롬프트를 통한 방 이미지 생성

| ![스케치](https://github.com/user-attachments/assets/8ffa87e8-0e6c-429b-8c31-09cb07e882cc) | ![이미지1](https://github.com/user-attachments/assets/e566ed5d-9a15-40c8-b4a8-70f1b0cf4e78) | ![이미지2](https://github.com/user-attachments/assets/a4825b5a-4fab-4d36-9af4-bee0ecd3ed0f) | ![이미지3](https://github.com/user-attachments/assets/2c6d092f-e4c6-4c09-a52a-352190e48a2c) |
|---|---|---|---|
| 스케치 | 이미지 1 | 이미지 2 | 이미지 3 |

- inpainting을 통한 방 이미지 생성 


https://github.com/user-attachments/assets/6460d9ae-ac98-4432-aa74-1dcded53cb7b


## Team

HaHaHa

|Name|Department|Contact|
|---|---|---|
| Kang Ji Hyun | Major of Bigdata | kangjihyunlo@naver.com|
| Hwang Seo Yeon | Major of Bigdata |cindyand1q2@gmail.com|
| Lee Gun Hee | Major of Smart IoT |sjwwiies2829@gmail.com|

## Coach

|Name|Department|Contact|
|---|---|---|
| Sung Hoon Lim | Hallym Univ (Prof.) |shlim@hallym.ac.kr|


## Install

```python
conda install -c conda-forge pyngrok  
conda install -c conda-forge flask-socketio  
conda install -c anaconda flask  
conda install -c conda-forge diffusers  
conda install -c conda-forge pytorch torchvision torchaudio cudatoolkit=11.8  
```

## Requirements
```
Python Version: 3.7 ~ 3.9

CUDA Version: 11.8
cuDNN Version: 8.1.1

Core Libraries:
- flask==2.0.3
- flask-socketio==5.1.0
- pyngrok==5.1.0
- diffusers==0.31.0
- pytorch==2.3.1
- torchvision==0.18.1
- transformers==4.46.2

Optional Tools:
- einops==0.3.0
- pillow==10.4.0
- tqdm==4.66.6
```




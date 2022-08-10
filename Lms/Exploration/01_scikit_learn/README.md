# Iris의 세 가지 품종, 분류해볼 수 있겠어요?

kaggle의 dataset을 사용해 기본적인 machine learning classification task을 실행하고, 빈도 높게 이용되는 model과 학습기법을 알아보자!

## 목차

- [개론](#개론)
- [문제 준비](#문제-준비)
  - [데이터 준비](#데이터-준비)
  - [데이터 조사하기](#데이터-조사하기)
- [모델 학습 및 평가](#모델-학습-및-평가)
  - [train, test 분할](#train-test-분할)
  - [training](#training)
  - [evaluation](#evaluation)
  - [모델 변경](#모델-변경)
- [모델 평가 방법](#모델-평가-방법)
  - [정확도의 문제점](#정확도의-문제점)
  - [어떻게 해결하는가?](#어떻게-해결하는가)
- [데이터 변경](#데이터-변경)
- [프로젝트](#프로젝트)
  - [손글씨 분류](#손글씨-분류)
  - [와인 분류](#와인-분류)
  - [유방암 분류](#유방암-분류)

## 개론

학습 목표

- scikit-learn의 dataset, classification model을 알고, 사용 가능
- 평가지표 종류를 알고, 사용 가능
- DT, XGB, RF, LR 알고, 사용 가능

## 문제 준비

사용할 lib 설치

```bash
pip install scikit-learn
pip install matplotlib
```

### 데이터 준비

***

`사이킷런(scikit-learn)`에 내장된 data 종류 파악
> [scikit-learn datasets site](https://scikit-learn.org/stable/datasets.html)
>
> - Toy datasets
>   - 집값 회귀
>   - 붓꽃 종류 예측
>   - 당뇨 정도 회귀
>   - 필기 숫자 예측
>   - 운동 종류 예측
>   - 와인 종류 예측
>   - 유방암 여부 예측
> - Real world datasets
>   - 얼굴 데이터
>   - 뉴스 주제 예측
>   - 얼굴 분류
>   - 나무 종류 분류
>   - 수동 분류 뉴스 와이어 기사
>   - 네트워크 통신 분류
>   - 주택 데이터

사용할 dataset은 붓꽃 종류 예측  데이터셋!

### 데이터 조사하기

***
데이터 로딩하기

```python
from sklearn.datasets import load_iris

iris = load_iris()
```

정보 확인

```python
iris.keys()
# dict_keys(['data', 'target', 'frame', 'target_names', 'DESCR', 'feature_names', 'filename', 'data_module'])
```

## 모델 학습 및 평가

### train, test 분할

***

### training

***

### evaluation

***

### 모델 변경

***

## 모델 평가 방법

### 정확도의 문제점

***

### 어떻게 해결하는가?

***

## 데이터 변경

## 프로젝트

### 손글씨 분류

***

### 와인 분류

***

### 유방암 분류

***

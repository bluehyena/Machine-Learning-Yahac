# Machine-Learning-Yahac

## Chapter 1. What is Machine Learning?

### Machine Learning - 기계학습
- A와 B제품을 구매한다는 상황을 가정. A, B의 특징으로는 수십여가지가 있다. 어떤 결정을 할 것인가?
- 숫자의 발명이후, 인류는 컴퓨터를 발명. 모든 계산을 컴퓨터에게 맡기게 됨. 인간의 고유한 영역이었던 결정(Decision)을 기계가 스스로 할 수 있도록 만듬. 이것이 바로 Machine Learning 즉, 기계학습임.
- 자동차가 발명되었다고 발이 쓸모없어지는 것이 아니며, 망원경이 개발되었다고 눈이 필요없는 것이 아니듯이, Machine Learning의 개발로 두뇌가 쓸모없어지는 것은 결코 아님.

### Machine Learning 의 세가지 KeyWord
- 원리
- 수학
- 코딩
- Machine Learning 자체를 다루는데에 반드시 수학과 코딩이 필요한 것은 아니다. 하지만, 언젠가 Machine Learning의 궁극적인 목표를 달성하기 위해서는, 반드시 수학과 코딩이 필요하다.

### 데이터셋의 다양한 이름

행(row)
- 개체 (instance)
- 관측치 (observed value)
- 기록 (record)
- 사례 (example)
- 경우 (case)

열(column)
- 특성 (feature)
- 속성 (attribute)
- 변수 (variable)  
- field

### 기계학습 (Machine Learning) 의 종류

1. 강화학습(reinforcement learning)
  - 현재의 상태(State)에서 어떤 행동(Action)을 취하는 것이 최적인지를 학습하는 것
2. 지도학습 (supervised learning)
* 분류(classification)
  - 공부시간에 따른 합격여부, 종양의 두께에 따른 악성종양의 양성 음성판단, 신체검사, 메일 발신인 제목 본문내용으로 스팸 메일 여부 판단, 고기의 지방함량, 지방색, 성숙도, 육색으로 등급 판단 등. 
* 회귀(regression)
  - 결과가 시간, 온도, 집 값,기온 변화량, 자동차 충돌 시 사망확률, 나이, 키 등의 숫자 데이터

3 .비지도학습 (unsupervised learning)
* 군집화 (clustering)
  - 비슷한 것 끼리 그룹을 만들어 배치.
* 연관 (association)
  - 관측치의 특성을 그룹화 해주는 것.
* 변환 (transform)

## Chapter 2. Tensorflow

Tensorflow가 사용되는 곳

* Supervised Learning
	- Regression
	- Classification

Deep Learning Library
* Tensorflow
* PyTorch
* Caffe2
* Theano

Algorithm
* Decision Tree
* Random Forest
* KNN (K-Nearnest Neighbor)
* SVM (Support Vector Machine)
* Neural Network Deep Learning

Supervised Learning Process
1. 과거의 데이터 준비
2. 모델 구조 생성
3. 데이터를 모델로 학습(Fit)시킨다.
4. 모델을 이용한다.

Loss 란?
* 학습의 진행도를 알려주는 지표
	- 독립변수를 모델에 넣어 나온 예측값, 실제 결과 값을 이용하여 Loss를 구함.
	- Loss 는 (예측값 - 결과값)^2 의 평균값임, 
	- Loss 가 0에 가까워질수록 정확한 모델임.

수식
* y = w1x1 + w2x2 + ⋯⋯ + w13x13 + b
 - 이 모델은 퍼셉트론(Perceptron) 이라고 부름.
 - 각각의 w들은 가중치(Weight) 라고 부름.
 - b는 편향(Bias)라고 부름.

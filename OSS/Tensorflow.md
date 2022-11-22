# 개요
- 구글에서 개발한 파이썬에서 사용 가능한 머신러닝 및 딥러닝을 위한 프레임워크이다.
- 데이터 획득, 모델 학습, 예측, 미래 결과 정제와 같은 과정을 쉽게 해줌
- C++로 구현되었으며 Python, Java, Go 등 다양한 언어를 지원함.
- Python을 최우선으로 지원하며 대부분의 편한 기능들이 파이썬 라이브러리로만 구현되어 있음
![image](https://user-images.githubusercontent.com/113485036/202982858-0de4c1f8-52c3-4ad9-b095-16a7bd06ff66.png)
- 시각화 도우미인 텐서보드를 제공하며 딥러닝 학습과정을 추적할 때 사용된다.
![image](https://user-images.githubusercontent.com/113485036/202982985-0d118acf-fc6a-4e73-8008-9bd9436cf0f1.png)


# 의미
- 텐서란 딥러닝에서 데이터를 표현하는 방식을 의미한다.
- 행렬로 표현할 수 있는 2차원 형태의 배열을 높은 차원으로 확장한 다차원 배열이다.
- 회색조 이미지는 하나의 채널에 2차원 행렬로 나타낼 수 있는 반면 RGB는 각 3개의 채널마다 2차원 행렬로 표현하는데 
이를 텐서로 표현할 수 있음  
![image](https://user-images.githubusercontent.com/113485036/202983272-b797e9ae-e6b9-477e-9b32-8eb665965514.png)
- 계산은 데이터 흐름 그래프로 이루어진다. 텐서형태의 데이터들이 딥러닝 모델을 구성하는 연산들의 그래프를 따라 흐르며 연산이 발생함.
- 딥러닝에서 데이터를 의미하는 텐서, 데이터플로우 그래프를 따라 연산이 수행되는 형태를 합쳐 Tensorflow 라고한다.  
![image](https://user-images.githubusercontent.com/113485036/202983318-e2c7a2bc-e74b-4168-9bdd-be85e9a18fc3.png)


# 추상화 및 사전 학습된 모델
- Keras나 TF-Slim 같은 추상화 라이브러리를 제공하여 저수준 텐서플로 라이브러리에 대해 손쉽게 고수준 접근이 가능하게 한다.
- 이를 이용하여 간단하게 딥러닝 모델을 구현할 수 있다.
- 아래 그림처럼 사전에 학습된 모델을 제공하며, 새로운 학습 필요없이 실무 적용이 가능하고 모델을 데이터에 맞게 조정할 수도 있다.  
![image](https://user-images.githubusercontent.com/113485036/202983446-414eb539-135f-40a8-a8a6-6c5139c1fb6f.png)

# 결론
- 가장 인기있는 딥러닝 라이브러리 중 하나이며, 텐서보드 및 Keras와 같은 추상화 라이브러리 그리고 사전에 학습된 모델을 통해
사용자가 딥러닝을 사용하는데 편리하게 해준다.
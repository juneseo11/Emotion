# 수치 예측

## - 선형 회귀

- 선형회귀는 종속 변수 y와 한 개 이상의 독립 변수(또는 설명 변수) X와의 선형 상관 관계를 모델링하는 회귀분석 기법이다.
- 한 개의 설명 변수에 기반한 경우에는 단순 선형 회귀, 둘 이상의 설명 변수에 기반한 경우에는 다중 선형 회귀라고 한다.
- y = Wx+b 직선을 그려놓고, 그 직선을 바탕으로 예측하는 방법이 선형 회귀이다.

![image](https://user-images.githubusercontent.com/57161820/68100970-7fc8c580-ff0e-11e9-8af4-01ca188d1332.png)

## -손실 함수, 경사 하강법

### 손실함수

- 신경망을 학습할 때 학습 상태에 대해 측정하는 하나의 지표로 사용한다. 
- 신경망의 가중치 매개변수들이 스스로 특징을 찾아 가기에 이 가중치 값의 최적이 될 수 있도록 해야 하며 잘 찾아가고 있는지 볼 때 손실함수를 보는 것이다.

최소 제곱 방법

- 식을 만들 때 최소 제곱 방법을 이용해서 구한다. 이 방법은 오차를 구하는데 효과적이다.
- 최소 제곱 방법은 차이나는 것을 한 변으로 취급하고, 정사각형의 넓이로 측정해 오차의 중요도를 높인다.

### 경사 하강법

- 경사 하강법은 1차 근삿값 발견용 최적화 알고리즘이다. 
- 기본 개념은 함수의 기울기를 구하여 기울기가 낮은 쪽으로 계속 이동시켜서 극값에 이를 때까지 반복시키는 것이다.

# 이진 분류

## -퍼셉트론

퍼셉트론은 다수의 신호를 입력 받아서 하나의 신호를 출력한다. 퍼셉트론의 동작은 노드의 가중치와 입력치를 모두 합한 값이 임계치보다 크면 활성화되고 1을 출력하며, 활성화 되지 않으면 결과값으로 0을 출력하는 것이다.

![image](https://user-images.githubusercontent.com/57161820/68101022-d7ffc780-ff0e-11e9-889f-f921bd7f5073.png)

## -로지스틱 회귀
- 로지스틱 회귀는 직선 대신, S자 곡선을 이용하여 분류에 정확도를 향상했다.
- 로지스틱 회귀분석은 반응변수가 1 또는 0인 이진형 변수에서 쓰이는 회귀분석 방법이다.
- 로지스틱 회귀는 선형 회귀 분석과는 다르게 결과가 범주형일때 사용한다.
ex) 학생이 문제를 맞을 것인지 틀릴 것인지, 내일 비가 올지 안 올지

## -시그모이드 함수
시그모이드 함수는 S자와 유사한 완만한 시그모이드 커브 형태를 보이는 함수이다.
시그모이드 함수는 대표적인 로지스틱 함수로 모든 실수 입력 값을 0보다 크고 1보다 작은 미분 가능한 수로 변환하는 특징을 갖는다.

![image](https://user-images.githubusercontent.com/57161820/68101031-e5b54d00-ff0e-11e9-959a-0126e033842e.png)

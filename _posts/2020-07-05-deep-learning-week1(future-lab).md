---
title : "Deep Learning 입문 (1)"
tag :
    - blog
---
언제 사라져도 이상하지 않은 Deep Learning 입문 (1) 

## 미래연구소에서 배워보는 Deep Learning 1주차
###### http://futurelab.creatorlink.net/

#### 모두를 위한 딥러닝 lec01 *기본적인 Machine Learning 용어와 개념 설명*
###### [모두를 위한 딥러닝 lec01](https://www.youtube.com/watch?v=qPMeuL2LIqY&list=PLlMkM4tgfjnLSOjrEJN31gZATbcj_MpUm&index=2)
- 전통적인(?) 방법의 프로그래밍은 인간이 직접 프로그램에 필요한 기능 혹은 rule들을 짜야하는 explicit programming이다. 하지만 점점 더 복잡한 프로그램, 적용해야 하는 rule이 너무 많은 프로그램을 만들기 위해서는 이것으로는 한계가 있다.
- Machine Learning은 말 그대로 기계가 학습을 하는 일종의 소프트웨어이다. data를 통해서 rule을 학습한다.
- 학습하는 방법에 따라서 supervised  learning과 unsupervised learning으로 나눌 수 있다. 
- supervised learning은 labeled data 즉 결과값을 알고 있는 data를 통해서 학습한다. 마찬가지 의미로 training set을 이용한다. ex) 개와 고양이 사진 구별
- unsupervised learning은  un-labeled data를 통해서 학습한다. ex) news grouping, word clustering
- supervised learning은 machine learning에서 가장 흔한 문제유형으로 앞으로 주로 다루게 될 것이다.
- supervised learning 의 종류에는 regression, binary classification, multi-label classification 등등이 있다.

#### Neural Networks and Deep Learning C1W1L02 *What is a Neural Network*
###### [C1W1L02](https://www.youtube.com/watch?v=n1l-9lIMW7E&list=PLkDaE6sCZn6Ec-XTbcX1uRg2_u4xOEky0&index=2)
- 주택가격을 예측하는 모델을 가정
- 주택의 가격에 영향을 미치는 특성들을 통해 가격을 예측함

#### Neural Networks and Deep Learning C1W1L03 *Supervised Learning with a Neural Network*
###### [C1W1L02](https://www.youtube.com/watch?v=BYGpKPY9pO0&list=PLkDaE6sCZn6Ec-XTbcX1uRg2_u4xOEky0&index=3)
- supervised learning : input x와 output y에 매핑되는 함수를 학습
- real estate, online advertising, photo tagging, speech recognition, machine translation, autonomous driving 등등...
- 구조적 데이터: 데이터 프레임으로 표현되는 데이터
- 비구조적 데이터: 음성파일, 이미지, 텍스트 등

#### Neural Networks and Deep Learning C1W1L04 *Why is Deep Learning taking off?*
###### [C1W1L04](https://www.youtube.com/watch?v=xflCLdJh0n0&list=PLkDaE6sCZn6Ec-XTbcX1uRg2_u4xOEky0&index=4)
- 딥러닝이 최근에 부상한 이유
- data, computation, algorithms의 3가지 조건이 충족됨
- big data의 생성
- computation 의 발전 = idea->code->experiment->idea 의 순환시간 감소
- algorithms의 발전 ex) sigmoid -> ReLu

#### 모두를 위한 딥러닝 ML lec02 *Linear Regression의 Hypothesis 와 cost 설명*
###### [모두를 위한 딥러닝 lec02](https://www.youtube.com/watch?v=Hax03rCn3UI&list=PLlMkM4tgfjnLSOjrEJN31gZATbcj_MpUm&index=4)
- linear regression
- hypothesis : $\ H(x) = wx + b$
- cost function(loss function) = $\ |H(x) - y|^2$
- minimize cost function : $\ cost(W,b) = \frac 1 m \sum_{i=1}^m (H(x^i) - y^i)^2 $

#### 모두를 위한 딥러닝 ML lec03 *Linear Regression의 cost 최소화 알고리즘의 원리 설명*
###### [모두를 위한 딥러닝 lec03](https://www.youtube.com/watch?v=TxIVr-nk1so&list=PLlMkM4tgfjnLSOjrEJN31gZATbcj_MpUm&index=6)
- gradient descent algorithm을 이용해 minimize
- $$$\ W := W - \alpha \frac 1 m \sum _{i=1}^m (W(x^i) - y^i)x^i  $$$
- 여러 다른 minimization problem 해결 가능
- cost function이 convex function 이면 항상 사용 가능

> 이 글은 글쓴이 본인이 스스로 정리하기 위해 작성되었다.

![나비그림](C:\Users\south\Desktop\namnam0518.github.io\image\butterfly.png)
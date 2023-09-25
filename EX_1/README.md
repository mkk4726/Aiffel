<img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=Exploration-1&fontSize=90" />

1. 프로젝트 1의 회귀모델 예측정확도가 기준 이상 높게 나왔는가? MSE 손실함수값 3000 이하를 달성
-> OK (약 2600)
2. 프로젝트 2의 회귀모델 예측정확도가 기준 이상 높게 나왔는가? RMSE 값 150 이하를 달성 
-> OK (146)
3. 시각화 요구사항이 정확하게 이루어졌는가? 각 프로젝트 진행 과정에서 요구하고 있는 데이터개수 시각화 및 예측결과 시각화를 모두 진행하였다.
-> OK (필요사항 + feature selection시 필요한 부분에 대해서도 추가로 진행했습니다)

# < 작성자 회고>
- 태민 : 프로젝트로 이렇게 직접 진행을 해보니 어려운 부분(hyperparameter 값 맞추기)도 있었고, 단계별로 진행하니 생각보다 재미있었고 공부할 의욕이 나는것 같습니다.
- 지원 : 프로젝트 1은 linear regression 을 LMS에서 배운 것을 그대로 diabetes 에 적용하였습니다. Regression 문제로써, 혈압을 맞추는것 같습니다. 442명 대상으로 총 10개의 피쳐가 있었습니다. Linear Regression 모델을 이루는 최소 단위는 model, gradient, 그리고 loss 인것을 알았습니다. 여기서 우리가 조절하였던 hyperparameter 인 learning rate와 train-test split 을 가지고, 성능을 올려서 기분이 좋았습니다.
- 김민규 : 역시 문제는 예상하지 못한 곳에 있구나... train과 test split시 분포의 중요성을 다시 한번 깨달았습니다.

### Hi there 👋

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=datastation7&theme=github_dark&show_icons=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=6810779s&layout=compact&theme=github_dark)

✍🏻 Recent blog posts

-  TIL
   -  Today I Learned의 약자이다.
   -  그 날 공부한 것들을 정리한 곳이다.
  
- Project
  - First project
    - SNIA는 SAN(Storage Area Network) 표준과 관련하여 70개 이상의 관련 업체가 구성한 국제 비영리 산업단체인데 여기서 데이터를 출처하였다.
    - Block I/O는 I/O작업이 진행되는 동안 유저 프로세스가 자신의 작업을 중단한채, I/O가 끝날때까지 대기하는 방식이다.
    - 이 방식을 도입해서 하드디스크가 과부하되는 것을 막고, 캐시 메모리가 필요성이 있다고 결론이 나왔다.
  
  -  Second project
     - 타이타닉 데이터를 활용해서 머신러닝 모델 중에서 GradientBoosting Classifier의 정확도가 가장 높게 산출되었다.
     - Grid Search 로 구한 가장 좋은 Hyper Parameter를 적용했을 때 모델 정확도가 0.85에서 0.82로 감소하였다.
     - Stacking 으로 구한 두 정확도 중 Train정확도보다 Test정확도가 낮았다.
     - 그 이유는 Cross Validation시 한 fold당 표본개수가 부족하기 때문이다.

  - Third project
    - 캐글 데이터를 이용해 당뇨병을 예측하는 프로젝트이다.
    - 고혈압 또는 뇌졸증이 있거나 계단을 오를 때 불편함을 겪는 경우 당뇨병 발병률이 더 높은 양상을 보였다.
    - Age features가 0부터 12까지 있고, 삭제를 했을 때는 0.90이 나오는데 삭제를 안 했을 경우에는 0.87로 나와서 Age features를 삭제하였다.
    - 머신러닝 중 성능이 가장 높은 모델은 Accuracy:0.7570, Recall:0.7987, PrecL0.7372, F1:0.7667지표가 가장 좋게 나왔으므로 Pycaret모델이 가장 좋은 모델이 판단되었다.
    - 딥러닝 중 성능이 가장 높은 모델은 Loss:0.5025, Accuracy:0.7533, Recall:0.8008, Precision:0.7268지표가 가장 좋게 나와서 Pipline적용한 모델이 가장 좋은 모델이라고 판단되었다.
    - 데이터가 대부분 이산형으로 정제되어 있어서 EDA 제약이 많아서 처음부터 전처리가 안 되어있는 데이터보다 모델 정확도가 떨어졌다.
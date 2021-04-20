# ML
### regression 
- preprocessing이 매우 중요
- outlier, null값, 불필요한 컬럼 제거 
- RMSE로 평가할때 classification과는 다르게 점수가 낮을수록 높은 성능
- MSE보다 RMSE를 쓰는 이유는 평균치와 조금 많이 다른 값이 들어왔을 때 오차를 엄청 크게 잡아주지 않기 위해서임

### PCA
- 원하는 explained variance ratio를 정하여 원하는 만큼 원본 데이터를 보존하면서 차원 축소를 할수 있음
- kernelPCA와 gridsearchCV를 이용하여 best_params_를 찾아 정확도를 높힐 수 있음
- 

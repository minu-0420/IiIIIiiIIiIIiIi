# IiIIIiiIIiIIiIi
ossw final

단일 classification 알고리즘으로는 파라미터 조정을 통한 정확도 보정에 유의미한 변화를 찾이 못했습니다.
따라서 여러 classification 알고리즘을 통해 voting 기법을 이용하고자 계획을 짜고 voting에 속할 알고리즘으로 KNN, SVC, Random Forest, MLP 를 이용했습니다.
각 알고리즘에서 하이퍼 파라미터를 GridSerachCV를 통해 정확도가 높은 상위 몇개의 파라미터로 선정했습니다.
이후 각 모델별로 정확도를 비교하여 voting에 쓰일 갯수를 결정하여 마무리하였습니다.

🔑 **PRT(Peer Review Template)**

- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부
        
        - ![image](https://github.com/ivvve/aiffel-repo/assets/154392651/09a96a39-29af-449c-8a37-904631fe57d9)
        - ![image](https://github.com/ivvve/aiffel-repo/assets/154392651/9b794f63-0ebe-4e82-b1ff-5d9079e30e62)
        - ![image](https://github.com/ivvve/aiffel-repo/assets/154392651/aede4ecf-deb8-43df-8a87-8cfba7f6d35a)
        - ![image](https://github.com/ivvve/aiffel-repo/assets/154392651/98ca172e-a76a-4ec2-b63c-2d3f17873125)

- [x]  **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**
    - [x]  모델 선정 이유:
        - GRU,LSTM,CNN모델을 비교하였습니다.
    - [x]  Metrics 선정 이유:
        - 이진분류를 위한 accuracy를 사용하였습니다.
    - [x]  Loss 선정 이유:
        - 모델 체크포인트 callback을 이용하여 최적의 loss, epoch를 선정했습니다.
         
        - ![image](https://github.com/ivvve/aiffel-repo/assets/154392651/d7443d52-2447-4dbc-bb59-9537d8e79765)


- [x]  **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)**
    - [x]  데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
    - [x]  하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
    - [x]  각 실험을 시각화하여 비교하였나요?
    - [x]  모든 실험 결과가 기록되었나요?
     
        - ![image](https://github.com/ivvve/aiffel-repo/assets/154392651/bc79b784-1a49-48e7-9b79-14b056e2373c)
        - ![image](https://github.com/ivvve/aiffel-repo/assets/154392651/c2f74261-212b-440d-9c78-b48526fcd029)
        - ![image](https://github.com/ivvve/aiffel-repo/assets/154392651/d4f9b3a5-7838-4eb4-a717-f6462ec0bff4)

- [x]  **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**
    - [x]  배운 점: RNN 계열인 GRU, LSTM 모델과 비 RNN 계열 모델을 비교하고자 CNN 모델을 사용하여 실험을 진행했다.
    - [x]  아쉬운 점: pretrained embedding을 사용하면 성능이 좋아질 것이라고 기대했지만 그렇지 않았다.
    - [x]  느낀 점: Transformer 계열 모델로 성능을 비교해보면 좋을 것 같다.
    - [x]  어려웠던 점: pretrained embedding을 사용하여 성능이 좋아지지 않은 이유에 대해 생각해 보았습니다.
       
        - ![image](https://github.com/ivvve/aiffel-repo/assets/154392651/332fea3b-ba56-454f-8f37-9b6cc7a346cb)



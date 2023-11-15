# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김민규
- 리뷰어 : 김태민


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
    </br>
    1. CutMix와 Mixup 기법을 ResNet50분류기에 성공적으로 적용하였는가?</br>
    2. 다양한 실험을 통해 테스크에 최적인 Augmenation 기법을 찾아내었는가?</br>
    3. 여러가지 Augmenation 기법을 적용한 결과를 체계적으로 비교분석하였는가?</br>
        - 해당 조건을 만족하는 코드를 캡쳐해 근거로 첨부<br/>
    1. CutMix + Augmenation, CutMix, Mixup의 적용한 데이터셋을 각각 ResNet 모델에 잘 적용했습니다.<br/>
    
    - CutMix + Augmenation 기법을 적용한 모델,<br/>
    ![image](https://github.com/mkk4726/Aiffel/assets/29370771/f9a4d641-de7d-4e97-a29a-3bba2712e3bd)
    
    - CutMix만 적용한 모델,<br/>
    ![image](https://github.com/mkk4726/Aiffel/assets/29370771/bafe923b-9b9c-4cef-b6f8-440f52b0e3c4)
    
    - MixUp만 적용한 모델<br/>
    ![image](https://github.com/mkk4726/Aiffel/assets/29370771/1d118ae1-dd3a-46c7-a12f-4eb32c88e6ee)<br/>

    2. 각 Augmenation 기법을 잘 적용했습니다. 좋은 성능을 보인 순서대로 표로 나타냈습니다.<br/>
    ![image](https://github.com/mkk4726/Aiffel/assets/29370771/6a446e78-1c56-4cc1-a3c4-a3398f180245)

    3. 기본 데이터셋, 기본 Augmenation, CutMix + Augmenation, CutMix, MixUp 적용한 결과를 시각화하여 잘 나타냈습니다.<br/>
    ![image](https://github.com/mkk4726/Aiffel/assets/29370771/486ad313-aa5a-49aa-b0cd-4daff5e31b6a)<br/>
    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.

    - 스터디 중에 그루분들에게 모델을 저장하는 방법과 기능들을 설명해주고 도움을 주었습니다.
    ![image](https://github.com/mkk4726/Aiffel/assets/29370771/393a2c0e-ec81-4f21-ab97-28acf34d9b82)

        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.<br/><br/>
    - 모델의 callback 함수를 사용하여 저장하여 사용했습니다.<br/>
    ![image](https://github.com/mkk4726/Aiffel/assets/29370771/82b70f36-a5e8-4285-bc37-826bbac5abdb)<br/>
    - 모델을 저장하는 SaveModelEveryEpoch 함수를 분석해보았습니다.<br/>
    ![image](https://github.com/mkk4726/Aiffel/assets/29370771/18c14557-bb21-493e-9f30-1625e2ef88d2)<br/>
    - 모델에 저장돼어 있는 history를 뽑아서 정리해보았습니다.<br/>
    ![image](https://github.com/mkk4726/Aiffel/assets/29370771/b4ece955-69e6-4ed8-b2d5-1796ed8c65b8)
        
- [X]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.<br/>
      - 잘 작성하였습니다.
      ![image](https://github.com/mkk4726/Aiffel/assets/29370771/baa1e66d-ffa8-4ebc-9bb9-3fba361335be)

        
- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 하드코딩을 하지않고 함수화, 모듈화가 가능한 부분은 함수를 만들거나 클래스로 짰는지
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화했는지
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.<br/>

    - 캡쳐 한 부분 말고도 여러 부분을 함수화 처리하여 최소한으로 잘 만들었습니다.<br/>
    ![image](https://github.com/mkk4726/Aiffel/assets/29370771/d8c2a23c-d5bd-4396-99a5-72fa1bb238fd)



# 참고 링크 및 코드 개선
```
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```

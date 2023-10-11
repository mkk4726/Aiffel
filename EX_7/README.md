# 프로젝트 플로우 살펴보기

![image](https://github.com/mkk4726/Exploartion/assets/68997408/afe5ba2b-2fea-40f8-9bce-1cfc18853cac)

# 회고
꽤 어렵게 느껴진 GAN 모델에 대해 많이 익숙해진 것 같아서 좋다.  
거의 이번 노드는 12시간 이상 소요된 것 같은데, 결국 잘 끝내서 뿌듯하다.  
전체적인 플로우를 obsidian의 excalidrwa를 이용해 그려봤는데, 정리가 너무 잘된다. 앞으로도 꾸준히 그려봐야겠다.  
   
loss부분에 l1 loss를 빼고 돌렸더니 엉망으로 나와서 고민하는 과정에서, GAN 모델에 l1 loss를 추가하면 성능이 향상된다는 부분을 체화할 수 있었다.  

epoch10과 epoch 50을 비교해봐도 큰 차이가 없는 것으로 보아 데이터가 부족하다고 판단된다.


# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김민규
- 리뷰어 : MyungJun Lee


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
      - The illustrating process of GAN is well-drawn and fulfills all the criteria
      <img width="939" alt="image" src="https://github.com/mkk4726/Exploartion/assets/129345591/a40e2326-8259-400e-bbda-d82602be5a94">
    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
      - reviewer can understand because of comprehensive annotations
      <img width="377" alt="image" src="https://github.com/mkk4726/Exploartion/assets/129345591/3c81d055-8408-4b27-8557-3cd71d52e016">

- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” ”새로운 시도 또는 추가 실험을 수행”해봤나요?**
      - the coder has done new methods for saving data
      <img width="380" alt="image" src="https://github.com/mkk4726/Exploartion/assets/129345591/935972a5-5296-48d0-8dfa-4d7fa6050531">
      <img width="433" alt="image" src="https://github.com/mkk4726/Exploartion/assets/129345591/973cb221-a5c2-4b16-b66c-dd41c8ccd67e">
        
- [X]  **4. 회고를 잘 작성했나요?**
      - the review is well-crafted
      <img width="835" alt="image" src="https://github.com/mkk4726/Exploartion/assets/129345591/f4c858e4-7fef-4d7e-a43d-540275978d1e">
        
- [X]  **5. 코드가 간결하고 효율적인가요?**
      - the code is simple and efficient

# 참고 링크 및 코드 개선
```
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```

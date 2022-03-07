# cloud_sia
### Welcome to GroomyRoom Cloud_SIA GITHUB!
![music-cloud-line-icon-linear-260nw-1658323474](https://user-images.githubusercontent.com/79895378/156993388-a1e8ff82-a524-4d7c-9837-ae9b9648aac5.jpeg)

## Introduction:

팀원 소개:
팀장. 안가영
팀원. 김태훈
팀원. 김혜지

## Group Time Table:

| 구분           | 기간           |   활동   | 상세 내용| 
| ------------- |:-------------:| -------:|-------:|
| 1주차: 논문 분석  | 1/19(수요일) ~ 1/21(금요일) |*Deeplabv3plus,Unet, HRnet *기획안 작성하기| *베이스 라인 모델 논문 분석, *미니 해커톤 기획안 작성 및 제출 | 
| 2주차. 베이스 라인 모델 코드 확인 및 분석  | 1/24 (월요일)  ~  1/28 (금요일)  | *논문 리뷰 *베이스라인 모델 코드 분석, *기초 EDA |* 데이터로더, 모델 학습 부분의 코드 분석, *train, label 데이터 수, 크기, 파일 형태 들 분석  
|3주차. 코드 분석 및 전처리 | 2/03(목요일) ~ 2/11 (금요일) | *베이스라인 모델 코드 분석, *데이터 전처리      | *데이터로더, 모델 학습 부분의 코드 분석, * 데이터 전처리 |   
| 4주차. 코드 튜닝 | 2/10 (목요일) ~ 2/17 (목요일) |  *모델 튜닝 및 학습 진행, *성능 개선점 도출, 중간 보고 발표 | *구름 데이터셋에 맞게 코드 튜닝 (데이터로더 수정, HRNet으로 모델 변경), * 멀티 VS 단일 Class 성늘 비교, per epoch-augmentation |
| 5주차. 성능 개선| 2/18 (금요일) ~ 3/4 (목요일) | *심화 EDA, *성능 개선 및 싫험, *이미지 전처리|*Augmentation Each Epoch, *EDA PIXEL IMAGE 분석, *히스토그램 이미지 분석, *히스토그램 평활화, *감마 보정, *이미지 컬러 스페이스 변환 |   
|6주차. 최종 검토 | 3/4 (목요일) ~ 3/8 (화요일) | *발표 자료 준비, *발표 연습, *성능 개선 및 실험 |* 최종 발표 준비, *성능 개선 및 실험|   
|촞 개발기간 | 1/19 (수요일) ~ 3/8(화요일) | *모두가 열심히 했다    |*모두가 열심히 했다 |

## 📓 Assignment:

**Satellite Cloud Image Semantic Segmentation**

**Level One ⭐:**  구름 검출 모델 구현:
DeeplabV3 + HRNet 모델 튜닝 하고 150 epoch 학습 진행하기. 

**Level Two ⭐⭐:** EDA를 통해 데이터 분석, 검출 모델 성능 향상:

1️⃣ Val 이미지 shape이 각기 다름 

➡ zero-padding 제일 큰 이미지 사이즈에 맞추기

➡️ 제일 작은 이미지에 맞춰서 이미지 crop 하기

➡️ train data와 동일하게 random cropping (train epoch수에 맞게 적절한 학습 epoch수 고려 필)


2️⃣ 단일 class VS 멀티 class

➡️ 잩은 구름, 옅은 구름, 그림자 3개의 class 동시검출과 단일 검출 시 성능 비교 실험

➡️ 단일 검출이 더 좋은 성능을 보일것이라 예상되지만,
라벨과 mIoU 계산을 위해 단일 출력된 predict를 어떻게 합칠 것인가에 대한 접근 중요

## 💬 발표 자료:
| **밢표:**   | **링크:** | 
| ------------- | ------------- |
| **중간 발표**  | [Link](https://www.google.com) |
| **최종 발표**  | Content Cell  |

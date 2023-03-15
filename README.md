# Computervision_Seminar(본 포스팅은 https://inhovation97.tistory.com/ 을 참고하여 만들었음을 알립니다)
## week2 과제
[week2 해설](https://github.com/mumukyung/Computervision_Seminar/blob/main/CV_seminar_week2_%EA%B3%BC%EC%A0%9C%ED%92%80%EC%9D%B4.ipynb)
#### 2주차 과제에서는 glob함수를 해당 경로에 있는 파일들의 경로를 전부 리스트로 얻어올 수 있다는것을 배웠습니다 
#### glob 함수를 이용하여 이미지들을 분배 해줄겁니다
![image](https://user-images.githubusercontent.com/113089206/222088360-bdcbb37c-2cb8-43e1-bb2f-99b908519631.png)
#### 순서는 이미지들의 상위경로를 만들어주고 train,valid,test별로 폴더를 만들어줍니다 이후 내부에 클래스 별로 또 폴더를 만들어줍니다
#### 자 이제 폴더안에 파일들을 스플릿을 해주는 함수를 작성하고 함수를 돌리면 아래 사진처럼 분배가 잘 된것을 볼 수 있습니다
![image](https://user-images.githubusercontent.com/113089206/222088962-d3d5bddc-f0e9-4bd4-b3f7-af7ef59a1012.png)
#### 작성자는 week2과제에서 폴더까지 만드는것은 수행을 했으나 사진을 분배하는것에서 막혔으나 제출 이후 풀이를 보면서 하나하나씩
#### 코딩후 조금씩 이해가 갔으나 다른 방법으로도 작성자가 시도를 해봐야겠다는것을 느꼈습니다.

## week3 과제
[week3 해설](https://github.com/mumukyung/Computervision_Seminar/blob/main/CV_seminar_week_3_%EA%B3%BC%EC%A0%9C%ED%92%80%EC%9D%B4.ipynb)
#### week3과제는 사진 분배후 dolphin,shark,whale 순으로 이미지 shpae과 함께 출력하고 임의의 이미지의 색깔별로 선을 넣는 과제입니다
##### 예시1)
![image](https://user-images.githubusercontent.com/113089206/222096978-5b0ae3db-22df-47c2-b50e-63f7f80529db.png)
##### 예시2)
![image](https://user-images.githubusercontent.com/113089206/222097199-fd5b3a6d-4039-4cac-ab00-64079d076d00.png)

#### 우선 예시1)에서는 cv2함수를 사용하여 이미지를 불러온후 cv2.resize를 사용하여 크기를 조정하여 ax.imshow 표시하는 방법으로 진행되었습니다
#### 이후 예시2)에서는 임의의 이미지를 cv2.imread를 사용하여 불러온후 색상 목록을 color_list정의합니다 그후 for문으로 높이 및 너비를 간격을 계산합니다
#### 마지막으로 plt.imshow를 사용하여 수정된 이미지를 plt.subplots을 사용하여 생성된 새 그림의 ax1개체와 함께 표시

## week4 과제
[week4 해설](https://github.com/mumukyung/Computervision_Seminar/blob/main/week4_%EA%B3%BC%EC%A0%9C%ED%92%80%EC%9D%B4.ipynb)
#### 과제는 아래와 같이 원래 0~255 픽셀 값을 가진 귀여운 돌고래 이미지는 Augmentation이 적용되어(train_class[0][0]) 이미지가 변형 되었다.
#### train_class[0][0] 데이터를 시각화 할 수 있도록 시각화 라이브러리가 요구하는 numpy 타입의 올바른 이미지 데이터로 되돌리는 역함수를 만들어 시각화 해오는 것.
#### 밑에 함수로 증강 이미지를 정규화 후 원래 형식으로 다시 돌립니다
![image](https://user-images.githubusercontent.com/113089206/222115788-6d677dd3-b264-44e4-9e53-59522f1eb15a.png)
#### 역함수 로직을 짠 이후 다시 이미지를 불러오게되면 이런 이미지를 불러올 수 있습니다
![image](https://user-images.githubusercontent.com/113089206/222119332-77bc3c69-9b9b-4a3e-b683-67579494be8a.png)

## week5 과제
[week5 해설](https://github.com/mumukyung/Computervision_Seminar/blob/main/modeling.ipynb)
#### 파이토치 모델링으로 모델을 구글드라이브에 저장후 이미지학습중 best_accuarcy를 뽑았습니다
![image](https://user-images.githubusercontent.com/113089206/225244576-0a6ec8ce-9f38-4790-99e6-25602b2d6179.png)
![image](https://user-images.githubusercontent.com/113089206/225244681-c08d5f36-1c18-4043-b639-7c0cb81800de.png)

## week6 과제
[week6 해설](https://github.com/mumukyung/Computervision_Seminar/blob/main/test_acc.ipynb)
#### 모델을 100epoch를 돌려서 나온 가중치를 이용하여
#### testloader를 생성후 최종성능을 평가하였습니다
![image](https://user-images.githubusercontent.com/113089206/225245259-60aff171-20e9-4d9c-aa4d-ff2747d05ecc.png)
![image](https://user-images.githubusercontent.com/113089206/225245958-838a7731-44c6-473e-9a0a-c2542fdaa9d7.png)





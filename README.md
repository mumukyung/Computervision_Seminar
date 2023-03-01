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





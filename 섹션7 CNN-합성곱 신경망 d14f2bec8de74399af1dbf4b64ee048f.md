# 섹션7. CNN-합성곱 신경망

생성일: 2022년 10월 15일 오전 10:50

# CNN(Convolutional Neural Network)


![Untitled](https://user-images.githubusercontent.com/22024442/195964316-b85083a8-96c8-4c10-949b-61a51175e093.png)

픽셀값은 0~255

단순한 특성 → 복잡한 특성 순으로 학습

![Untitled 1](https://user-images.githubusercontent.com/22024442/195964173-96c42a8d-a345-486e-aa73-b043ab95b0e5.png)



![Untitled 2](https://user-images.githubusercontent.com/22024442/195964195-88204619-4c2b-4ea8-bdfc-91b9c4aca431.png)

학습은 합성곱층에서만 이루어짐

(필터를 만들어가는게 학습)

![Untitled 3](https://user-images.githubusercontent.com/22024442/195964202-07f1d94d-abbd-49ae-b9f6-e1e93c40f6d1.png)



![Untitled 4](https://user-images.githubusercontent.com/22024442/195964210-f094e8ad-1b4d-45df-8b5b-7ab36e46a196.png)

바깥쪽에 정보가 있는경우 0픽셀 패딩 적용

stride2로 하면 손실은 많지만 빠름

![Untitled 5](https://user-images.githubusercontent.com/22024442/195964213-532c7103-5fa5-46e7-aa6d-b06a7f8f877d.png)

![Untitled 6](https://user-images.githubusercontent.com/22024442/195964215-4d4908fa-427f-4d23-9a32-daf1c91f12a5.png)

![Untitled 7](https://user-images.githubusercontent.com/22024442/195964221-e03c9518-5fbf-457e-b58f-22a6166835b7.png)





각각의 rgb를 통해 convolution해줌

![Untitled 8](https://user-images.githubusercontent.com/22024442/195964244-0fbd6c67-cc6e-43a9-8197-f9dcb3c62a6f.png)
![Untitled 9](https://user-images.githubusercontent.com/22024442/195964247-b8f89eac-388e-4996-83d6-fd07d1db12e8.png)
![Untitled 10](https://user-images.githubusercontent.com/22024442/195964248-f6ad2d1f-ceeb-45ae-846a-6b064567d190.png)

![Untitled 11](https://user-images.githubusercontent.com/22024442/195964268-3b154ca7-a2b5-42d8-a431-dea36a36afe1.png)
![Untitled 12](https://user-images.githubusercontent.com/22024442/195964269-18d12e05-c789-44be-93d9-f36cf3205aad.png)

max pooling →각 구역에서 큰 값(현대에는 주로 이게 쓰임)
![Untitled 13](https://user-images.githubusercontent.com/22024442/195964283-c55017d6-76c7-474c-839a-68ddb399406c.png)
![Untitled 14](https://user-images.githubusercontent.com/22024442/195964284-122d88bb-1d45-48fc-b513-0320031a3ac5.png)
![Untitled 15](https://user-images.githubusercontent.com/22024442/195964285-8b59be74-e71c-4295-b4d3-d8cb60955078.png)


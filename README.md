# 대한상공회의소 딥러닝 기반의 주가 예측 서비스

## SETTING
### 가상환경 생성
    python -m venv venv

### 라이브러리 설치
    pip install django
    pip install djangorestframework
    pip install pandas
    pip install matplotlib
    pip install tensorflow
    pip install eunjeon

### eunjeon 라이브러리 설치 안될 때
![pip install eunjeon Error](https://raw.githubusercontent.com/IIBlackCode/KCCIST_FINALPROJECT/master/%EC%84%B8.%EB%82%98.%EC%A3%BC%20-%20%EB%94%A5%EB%9F%AC%EB%8B%9D%20%EA%B8%B0%EB%B0%98%EC%9D%98%20%EC%A3%BC%EA%B0%80%20%EC%98%88%EC%B8%A1%20%EC%84%9C%EB%B9%84%EC%8A%A4/install%20eunjeon.png)

---
---

# 5조 세.나.주 - 세상에 나쁜 주식은 없다.

## 대한상공회의소 프로젝트 경연대회 대상 수상작

![슬라이드0001](https://user-images.githubusercontent.com/46194003/147877943-e65678b9-fa28-411c-8e00-26b48e1dab44.jpg)
![슬라이드0002](https://user-images.githubusercontent.com/46194003/147877944-4c318ade-233b-4d98-9c00-f28000f61779.jpg)
![슬라이드0003](https://user-images.githubusercontent.com/46194003/147877945-ca483336-3626-4647-8385-2d0abd55f394.jpg)
![슬라이드0004](https://user-images.githubusercontent.com/46194003/147877946-a3bf4069-aa4b-448c-8d4d-af8cebc784a3.jpg)
![슬라이드0005](https://user-images.githubusercontent.com/46194003/147877948-9ae0b015-f746-4d6f-8ae0-e2b82ae104d3.jpg)
![슬라이드0006](https://user-images.githubusercontent.com/46194003/147877949-8dae878e-3865-4c00-b230-42c33a3bad78.jpg)
![슬라이드0007](https://user-images.githubusercontent.com/46194003/147877952-a97a0d4c-f236-45aa-b039-b6176b31d234.jpg)
![슬라이드0008](https://user-images.githubusercontent.com/46194003/147877953-9a2a26e9-ac04-45a0-af55-bbf7b3df1c93.jpg)
![슬라이드0009](https://user-images.githubusercontent.com/46194003/147877955-9ac549f5-09bd-418c-bf23-4f500e08d90a.jpg)
![슬라이드0010](https://user-images.githubusercontent.com/46194003/147877956-2530574e-7188-4f04-b141-ca32bc0680aa.jpg)
![슬라이드0011](https://user-images.githubusercontent.com/46194003/147877957-a9fa19fb-bdce-45e1-9e5a-2d3c9fe28cd0.jpg)
![슬라이드0012](https://user-images.githubusercontent.com/46194003/147877960-e7177f9d-b57e-40e7-af10-d7b0ee5bffe3.jpg)
![슬라이드0013](https://user-images.githubusercontent.com/46194003/147877961-585a126c-9c4f-485a-a971-cf55626acbcb.jpg)
![슬라이드0014](https://user-images.githubusercontent.com/46194003/147877963-0abc1fd7-c351-4594-973c-2305e7edf5ee.jpg)
![슬라이드0015](https://user-images.githubusercontent.com/46194003/147877964-eedd0705-26b6-43a7-a6d7-e3327ba1ec6a.jpg)
![슬라이드0016](https://user-images.githubusercontent.com/46194003/147877966-390b83eb-a428-42ed-bbc9-554a27afa372.jpg)
![슬라이드0017](https://user-images.githubusercontent.com/46194003/147877967-4be95d23-5851-43ac-af7b-ac4ce6e97413.jpg)
![슬라이드0018](https://user-images.githubusercontent.com/46194003/147877968-72c07984-6930-4e1c-8778-8b1fe8687da1.jpg)
![슬라이드0019](https://user-images.githubusercontent.com/46194003/147877969-5c04c6c3-c96d-4003-ae47-4f985c8f75c5.jpg)
![슬라이드0020](https://user-images.githubusercontent.com/46194003/147877971-d4ac27be-953d-44dd-84c0-fa07b00d06b6.jpg)
![슬라이드0021](https://user-images.githubusercontent.com/46194003/147877972-f77fe585-ed26-4205-a355-86271287a980.jpg)
![슬라이드0022](https://user-images.githubusercontent.com/46194003/147877973-be0bdda1-bf3b-4cdc-97d8-9bba5687c208.jpg)
![슬라이드0023](https://user-images.githubusercontent.com/46194003/147877974-b9f82000-4060-4248-a2fd-a9bf658658a9.jpg)
![슬라이드0024](https://user-images.githubusercontent.com/46194003/147877975-da3e3c6d-c180-46ec-b73a-cf2d654bb29e.jpg)
![슬라이드0025](https://user-images.githubusercontent.com/46194003/147877976-448135f5-70ce-4e09-a57b-4b31b8947994.jpg)
![슬라이드0026](https://user-images.githubusercontent.com/46194003/147877977-16020cb1-0788-42e6-a76f-6cfb9ffd8b21.jpg)
![슬라이드0027](https://user-images.githubusercontent.com/46194003/147877978-b5a48db0-c1e4-4f5b-a786-408c22d7537b.jpg)
![슬라이드0028](https://user-images.githubusercontent.com/46194003/147877979-53a9f379-3624-43aa-961d-88199dd2c8a2.jpg)
![슬라이드0029](https://user-images.githubusercontent.com/46194003/147877980-297e262c-6e64-4547-a8e5-5326305549d4.jpg)
![슬라이드0030](https://user-images.githubusercontent.com/46194003/147877981-b59ed5d8-05aa-4aae-b2ff-b721926623aa.jpg)
![슬라이드0031](https://user-images.githubusercontent.com/46194003/147877984-7b95ad4a-749f-4250-91f0-99e1ae7c7696.jpg)
![슬라이드0032](https://user-images.githubusercontent.com/46194003/147877987-98b6ce2c-45ec-4e3e-b1da-67d75ff8e5be.jpg)
![슬라이드0033](https://user-images.githubusercontent.com/46194003/147877988-48d3f77a-c49e-48b5-8831-ea2624619484.jpg)
![슬라이드0034](https://user-images.githubusercontent.com/46194003/147877989-238732e5-87e5-4d23-9906-376a096f7844.jpg)
![슬라이드0035](https://user-images.githubusercontent.com/46194003/147877991-f94edd63-228d-45c3-b9da-1c5f48f11f5c.jpg)
![슬라이드0036](https://user-images.githubusercontent.com/46194003/147877992-f410c65c-a478-46c2-bd6b-f57c0253e8d1.jpg)
![슬라이드0037](https://user-images.githubusercontent.com/46194003/147877994-20860938-ec48-4f76-a154-6727a45656ad.jpg)
![슬라이드0038](https://user-images.githubusercontent.com/46194003/147877995-25312bd8-dcbe-4965-8166-f64b15c877bb.jpg)
![슬라이드0039](https://user-images.githubusercontent.com/46194003/147877997-03e5a04f-5c15-488f-80d4-146f6f4e39d5.jpg)
![슬라이드0040](https://user-images.githubusercontent.com/46194003/147877998-a9a253e8-04db-44ba-a213-152285027ab8.jpg)
![슬라이드0041](https://user-images.githubusercontent.com/46194003/147877999-5a31d842-828e-4164-a993-5ede28a40307.jpg)

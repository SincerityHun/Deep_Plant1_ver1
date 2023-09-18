
# Deep Plant1 Project

  

## 1. Team

  

- 멘토: 황영숙 교수님

- 정성훈(SincerityHun)

- 박수현(clapsh)

- 전수현(junsu0573)

- 김성중(qpwozxc)

- 송의영(hosicuro)

  

## 2. Roles

  

1. Backend
	- 정성훈

2. App

	- 전수현
	- 송의영
3. Web
	- 김성중
	- 박수현

  

## 3. Development Contents

  

1. Mobile Application

	- 카메라 연동을 통해 육류 이미지를 촬영 및 관능 데이터 입력/수정/조회 기능 탑재

2. Server

	- 데이터 수집/저장 및 관리를 위한 DB 서버

	- 데이터 통계 분석 및 어드민 관리 기능을 탑재한 데이터 분석 서버

  

## 4. Server Local Installation

  

1. Docker 설치

2. Repository Clone

3. [Google Drive](https://drive.google.com/drive/u/0/folders/1RW4xZzp80IGxzYLu9gwnFegA9Orpy73z)에서 keyId.py & serviceAccountKey.json 파일을 "Deep_Plant1/Backend/" 안에 넣어두기

4. Dockerfile Image build

	```bash

	cd  Deep_Plant1

	docker  build  -t  flask-app  .

	```

5. Docker container run

	``` bash

	docker  run  -p  8080:8080  flask-app

	```

6. Local Server 접속

	- https://localhosts:8080
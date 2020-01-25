## 도커 빌드
```shell
docker build --tag docker-node:dev .
docker images // 이미지 생성 확인
docker run --name docker-node-container -p 80:80 docker-node:dev// 만든 이미 실행
```
"# final-personalProject" 

# 구현 Repository
- https://github.com/gyong1209/b-information

### 1. 이벤트 스토밍

## 팀과제 완성된 모형
![완성1](https://user-images.githubusercontent.com/25577890/91920135-1f0f4280-ed03-11ea-8a73-a0f939928ead.PNG)

## 서비스 
![이벤트 스토밍](https://user-images.githubusercontent.com/53261680/92063969-6109b880-edd7-11ea-8a30-73afb2a287c8.PNG)

### 2. 비동기 호출
 - 수신쪽 pod삭제후, 비동기 호출
![받는쪽 내린상태에서 비동기호출](https://user-images.githubusercontent.com/53261680/92065267-543a9400-edda-11ea-83b3-9c08bcfe2252.PNG)

 - 수신쪽 올린상태에서 카프카 이후 수신 확인
 ![서버 올린후 카프카 비동기 수신](https://user-images.githubusercontent.com/53261680/92065319-73d1bc80-edda-11ea-8beb-415dbcfe4e64.PNG)


### 3. 동기 호출
  - user 삭제 동기호출
  ![delete user](https://user-images.githubusercontent.com/53261680/92065352-84823280-edda-11ea-9829-77bd4f920b81.PNG)
  
  - 카프카쪽 수신 확인
  ![update information kafka](https://user-images.githubusercontent.com/53261680/92065553-e2167f00-edda-11ea-81e8-ccab3455545a.PNG)
  
  - information 상태 변경 확인
  ![update information kafka](https://user-images.githubusercontent.com/53261680/92065480-c4491a00-edda-11ea-9ea2-a7e88de8d1d3.PNG)


### 4. 게이트웨이
![게이트웨이 인증](https://user-images.githubusercontent.com/53261680/92065837-5ea95d80-eddb-11ea-8f25-d596648c0d9a.PNG)
![게이트웨이 인증2](https://user-images.githubusercontent.com/53261680/92065839-5f41f400-eddb-11ea-848e-59ccb523ed0b.PNG)

### 5. CQRS


### 6. AutoScale out



### 7. 무정지배포

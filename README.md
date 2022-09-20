# dongjak_bigdata
**네이버 지도 크롤링 데이터를 기반으로 관광지 빅데이터 분석 및 정책 제안**

## Summary
**crawling을 통해 3종류의 Raw big data 수집**  
1. '대한민국 구석구석' 웹페이지에서 대한민국의 모든 관광지 목록 크롤링  
2. 네이버 지도의 관광지 주변 환경 (음식점, 카페, 숙박, 교통, 술집, 공원, ....) 자동 검색으로 크롤링  
3. 관광지별 리뷰 자동검색 및 개수 크롤링  

**통계분석을 기반으로 동작구의 역사,문화 관광에 도움이 되는 정책 아이디어 제안**  
- 관광지 주변 환경이 리뷰에 미치는 영향 상관분석  
- 선형회귀분석을 통해 Review의 수와 선형관계가 있는 요소 추출  

### Data analysis
1. linear regression으로 약 1000개의 관광지 P의 관광요소 집합 X(공원, 명소, 숙소, ..) 와 Y(Review의 수)의 선형관계를 분석하여 각각의 X요소가 Y와 어떤 관계가 있는지를 weight에 따라 분석해봄
2. t-test를 통해, p-value가 0.05 미만인 관광요소:교통, 숙소, 술집이 Review 수와의 선형적 관계가 성립함을 밝힘
 
-------------

![0001](https://user-images.githubusercontent.com/61912635/87799809-a0606200-c888-11ea-8d0c-606aaf9f859a.jpg)
![0002](https://user-images.githubusercontent.com/61912635/87799813-a1918f00-c888-11ea-8649-6109f2174aaf.jpg)
![0003](https://user-images.githubusercontent.com/61912635/87799820-a35b5280-c888-11ea-8458-68222b30173b.jpg)
![0004](https://user-images.githubusercontent.com/61912635/87799823-a48c7f80-c888-11ea-98ee-ab20802bf73b.jpg)
![0005](https://user-images.githubusercontent.com/61912635/87799830-a5bdac80-c888-11ea-911d-7e58b001d0c3.jpg)
![0006](https://user-images.githubusercontent.com/61912635/87799840-a8b89d00-c888-11ea-9e3d-14c488784c19.jpg)
![0007](https://user-images.githubusercontent.com/61912635/87799931-ca198900-c888-11ea-9fb9-f2a66880aba9.jpg)
![0008](https://user-images.githubusercontent.com/61912635/87799926-c8e85c00-c888-11ea-8d7e-309c1f2e6878.jpg)
![0009](https://user-images.githubusercontent.com/61912635/87799957-d271c400-c888-11ea-82bb-b3558b440aaa.jpg)
![0010](https://user-images.githubusercontent.com/61912635/87799963-d43b8780-c888-11ea-9e0a-9b6d34264b98.jpg)
![0011](https://user-images.githubusercontent.com/61912635/87799970-d56cb480-c888-11ea-9019-73ca597bccd1.jpg)
![0012](https://user-images.githubusercontent.com/61912635/87799977-d7367800-c888-11ea-9319-8fb7c0466222.jpg)
![0013](https://user-images.githubusercontent.com/61912635/87799984-d867a500-c888-11ea-81a6-4c7da70454b2.jpg)
![0014](https://user-images.githubusercontent.com/61912635/87799990-d9003b80-c888-11ea-9cbe-7b5a9066e2cc.jpg)
![0015](https://user-images.githubusercontent.com/61912635/87799992-da316880-c888-11ea-98f6-2227936f82ef.jpg)
![0016](https://user-images.githubusercontent.com/61912635/87799998-db629580-c888-11ea-995d-9144cb20574a.jpg)
![0017](https://user-images.githubusercontent.com/61912635/87800001-dc93c280-c888-11ea-8595-ae51c4d2a5bf.jpg)
![0018](https://user-images.githubusercontent.com/61912635/87800007-ddc4ef80-c888-11ea-9f1d-cc0cb6380987.jpg)
![0019](https://user-images.githubusercontent.com/61912635/87800016-def61c80-c888-11ea-8083-671143e35698.jpg)
![0020](https://user-images.githubusercontent.com/61912635/87800021-e0274980-c888-11ea-8720-cc88c0decf13.jpg)
![0021](https://user-images.githubusercontent.com/61912635/87800027-e1587680-c888-11ea-9aea-3553225ed885.jpg)
![0022](https://user-images.githubusercontent.com/61912635/87800038-e289a380-c888-11ea-8316-757a8212218e.jpg)
![0023](https://user-images.githubusercontent.com/61912635/87800065-ea494800-c888-11ea-9c80-6c4e0097d2b1.jpg)
![0024](https://user-images.githubusercontent.com/61912635/87800045-e4ebfd80-c888-11ea-9812-bb9fdd150e46.jpg)
![0025](https://user-images.githubusercontent.com/61912635/87800049-e61d2a80-c888-11ea-9e8e-82ed4423215c.jpg)


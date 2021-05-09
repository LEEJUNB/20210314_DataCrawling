# DataCrawlingScrapping
## 프로젝트의 목표 및 순서
* 목표 : 크롤링, 스크래핑 기술 습득
- 정형, 비정형 데이터를 효과적으로 수집 저장
- Next Step. 전처리, 시각화(WordCloud, Mapping, plotting 등), 각 변수들 간의 상관관계를 파악

## 데이터 수집 대상
- 네이버 : 주식, 모바일 View, 이미지
- 다나와 쇼핑, 코로나 통계, 인터넷 강의 댓글, 청와대 국민청원, 멜론 음원 차트 등
- 인스타그램 이미지
- 인공지능, 빅데이터 키워드를 가진 뉴스, 레포트
- 교육, 채용, 컨퍼런스, 해커톤, 공모전 정보

## 환경
- IDE : JupyterNotebook
- Language : Python3
- Library : BeautifulSoup(HTML 태그에서 필요한 정보 추출), webdriver(Selenium 라이브러리_크롬 웹브라우저 제어)

## 주의사항
특정사이트에서 짧은 시간 동안 많은 데이터를 수집할 시 디도스 공격 등으로 감지되거나 웹 서버에 무리를 줄 수 있음.

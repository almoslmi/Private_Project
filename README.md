# Personal Project   
---------------------------  
## Description  
1. 데이터 수집  
>  일별로 카테고리별 랭킹에 따라 뉴스를 크롤링  
> * 네이버, 다음  
> * 뉴스는 본문,  신문사  
> * 해당 뉴스에 대한 전체 댓글 내용과 각 댓글의 공감/비공감 수
>> * 이모티콘으로만 구성된 댓글은 배제함.

2. 데이터베이스 구축  
> 크롤링을 통해 데이터를 저장할 데이터 베이스를 구축  
> * mongoDB 중 선택  
> * DB 구축  

3. 웹 구축  
> Flask를 이용하여 Amazone Web Service(AWS)에 웹 구축

3. 키워드 분석  
> * 뉴스 본문의 키워드 추출 (빈도수)  
>> * 다음의 경우, 키워드가 제시되어 있으며, 추가 코드로 만들어진 키워드와의 차이를 비교할 수 있음  

4. 감정 분석  
> * 추출된 키워드에 대하여 뉴스 내용이 긍정적인지 부정적인지 분석  
> * 뉴스의 댓글들에 대하여 감정 분석  
> * 뉴스 본문에서의 분석되는 감정과 해당 뉴스의 댓글에서 분석되는 감정 사이의 차이를 비교할 수 있다    

5. 분석  
> * 신문사, 키워드 등의 정보를 이용하여 분류  
> * 신문사, 키워드 등의 정보를 이용하여 클러스터링  
> * 시각화 작업  
>> * 키워드 사이의 연관성을 보여주는 그래프를 보여줄 수 있다.   
---------------------------  

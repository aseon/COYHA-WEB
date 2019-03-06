# 레이아웃 잡기.  

간단하게 게시판 형식의 레이아웃만 잡아볼 예정입니다.  

## 문제  
1. 'Classified Advertisement'에 마우스 오버시 0.5s || 즉시 상하 반전.  
2. 첫번째 Post에 마우스 오버시 아무런 동작 없도록.  
3. 짝수 post 라인에 마우스 오버시 백그라운드 컬러 '#b5b2ff', post title에 마우스 오버시 title 이름 컬러 'black'으로 변경  
4. 홀수 post 라인에 마우스 오버시 백그라운드 컬러 '#aee1ff', post title에 마우스 오버시 title 이름 컬러 '#3e15ff'으로 변경  
5. pagenation의 숫자에 마우스 오버시 0.5s로 백그라운드컬러'#00ccff' , border-radius 좌상,우상,좌하,우하를 5px로 작성.  

## 전제조건  
1. maxwidth는 80% 이다.  
2. headerArea와 boardArea 의 간격은  50px 이다.
3. pagenation의 상하 간격은 20px 이다.
4. boardArea의 간격은 20px이다.  

## 사용권장하는 CSS Peseudo Selector    
1. :first-child  
2. :first-of-type()  
3. :nth-child()   
4. :nth-of-type()  
5. :not(:pseudo)  




p.s.   
백그라운드 컬러, 컬러, 등은 아무렇게 넣어주시면 됩니다. 지정된 색 이외에 본인이 좋아하는 색깔로 대체해주세요~~
각 컨텐츠의 여백을 취미대로 넣으셔도 되며, 자신이 예뻐보이는 만큼의 수치를 입력해주세요!!!!


__예제이미지는 Project_004의 project_004.png 입니다.__
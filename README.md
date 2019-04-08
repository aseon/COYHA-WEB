# Release  
- 2.0.19.01v : 실행 불가능한 부분 취소선 처리
- 2.0.19.02v : 제출기한 폐지 및 프로젝트 진행 관련 추가
- 2.0.19.03v : 일부 gitHub User 링크 추가  및 함께하는 분 추가  
- 2.0.19.04v : 새로운 멤버 추가, 새로운 프로젝트 폴더 생성 및 파일 추가  
- 2.0.19.05v : Project_003이 시작되었습니다.   
- 2.0.19.06v : Project_004가 시작되었습니다.  

## 들어가며
> 코딩야학의 디스코드에서 주최되었으며, 참여와 진행은 자유롭게 하시면 됩니다.  
> '코딩을 손에 익히자, 남의 코드를 많이 보자, 일단 만들어보자' 가 이 스터디의 가장 큰 취지입니다.  

HTML 과 CSS 더불어 javascript를 사용할 수 있으신 분들은 본인의 역량을 발휘하여 페이지를 만들어 가려고 합니다. 가능하다면 **코드리뷰**와 **서로 도움 주고받기** 를 할 예정이며 할 수 있는 만큼 지치지 않고 재밌게 꾸준히 했으면 하는 바람에 만들었습니다.  

1. **주제(시안)** 는 리더 혹은 **멤버전체** 가 정합니다.
2. **이미지,동영상**는 작성자가 넣고싶은것을 아무거나 골라서 넣으시면 됩니다. (이미지를 따오는 시간을 줄이고자 함)
3. **시안**을 가지고 있거나, 공유해도 되는 것이라면 포토샵을 이용해 이미지를 따는 과정까지 포함 할 수 있습니다.
4. **제출기한**은 초반에는 넉넉히, 시간이 흐를수록 짧게 잡도록 하겠습니다. (스터디 도중 참여자는 처음 제출기한으로 맞춥니다.)  
~~* 제출기한: 3weeks to 3days~~
* 제출기한 관련 공지: 제출기한을 폐지합니다. 자유로운 기간에 마무리 할 수 있도록 조정했습니다. 수행중인 Project를 완성한 후에 그 다음 Project를 진행하면 됩니다.
5. > 부담갖지 말고 즐기면서 하면 됩니다.  
6. ~~**Github Organization 사용을 기본으로 하고 사용에 미숙한 분들은 리더 혹은 멤버가 '멤버'의 폴더에 파일을 업로드 해줍니다.**~~
7. ~~모두가 하나의 `master-branch`를 사용하며 `commit`만 합니다. 업로드 할 시, 본인의 폴더 이외에는 건들지 않습니다. `push`는 `repository`의 `master/origin`이 합니다.~~
8. github Basic Folder Root
Organization (COOHYA-WEB) -master/origin   
│      
main root      
    │   
    └ personal folder   
      │   
      └ project_1 folder   
        │   
        │ css     
        │ js   
        └ index.html   
기본적인 폴더는 _개인폴더(고정)_->_프로젝트폴더(고정_)->   
프로젝트폴더 안의 파일 혹은 폴더는 본인 취향껏 만들면 됩니다. (eg. css,js,html)  

## 1.공부방법
- 웹사이트를 리뉴얼할 경우 개발툴을 **열지 않고** 본인만의 마크업과 CSS로만 작성합니다.  
- 레이아웃을 작성할 때에는 웹 표준과 웹접근성에 근거하여 작성합니다.  
- 의미있는 태그와 의미없는 태그를 구분하며 작성합니다.  (eg. strong / em / b )  
- CSS 작성시 본인의 스타일대로 작성할 수 있습니다.  
- 막히거나, 모르는 부분은 **충분히 검색한 후**에 다른사람의 의견을 물어봅니다.  

## 2.참고 할 만한 사이트
[Caniuse](https://caniuse.com/) // css가 보편적으로 사용되는지 알려주는 사이트   
[W3CShcool](https://www.w3schools.com/) // 프로그래밍 언어의 전반적인 사용법을 알려주는 사이트   
[CSS 작성 수칙](https://nuli.navercorp.com/data/convention/NHN_Coding_Conventions_for_Markup_Languages.pdf) // 네이버코딩컨벤션  
[W3C웹표준 검사](https://validator.w3.org/) // 웹표준 검사  
[W3C CSS 검사](http://jigsaw.w3.org/css-validator/)  
[Dirty MarkUp](https://www.10bestdesign.com/dirtymarkup/) // HTML 코드를 정돈해주는 온라인 도구   
[Reset CSS](https://meyerweb.com/eric/tools/css/reset/) // CSS작성  
[Responsive web tester](http://troy.labs.daum.net/)   

## 3. 권장되는 CSS 작성 규칙 및 순서

| 순서 | 속성 | 의미 |
|:--------:|:--------:|:--------:|
|1| display | 표시 |  
|2| overflow | 넘침 |  
|3| float | 흐름 |  
|4| position | 위치 |  
|5| z-index | 정렬 |  
|6| width & height | 크기 |  
|7| margin & padding | 간격 |  
|8| border | 보더 |  
|9| font | 폰트 |  
|10| background | 배경 |  
|11| 	etc(기타) | color,text-decoration,text-indent,clear... |        


권장되는 CSS작성순서 일 뿐이며 이미 본인의 스타일이 있으시다면 **본인의 스타일**대로 작성하시면 됩니다.   
     
## 4.스터디 진행도

1. Project_001:  
    - 주제: Global Natonal Geographic **mainPage Renewal** 글로벌 내셔널지오그래픽 메인페이지 리뉴얼
    - URL: [Natonal Geographic](https://www.nationalgeographic.com/)    
    - 시작일: 2019-01-24
    - 종료일: -
  
2. Project_002:
   - 주제: Tajam Web page make  
   - URL[Tajam Sources](https://github.com/Christianpark/COYHA-WEB/tree/master/COYHA-WEB/000_ProjectFiles)  
   - 시작일: 2019-02-07  
   - 종료일: -  

3. Project_003:  
   - 주제: layOut연습.html  
   - URL[layOut연습](https://github.com/Christianpark/COYHA-WEB/tree/master/COYHA-WEB/000_ProjectFiles/template/project_003)  
   - 내용: readMe.md를 읽고 해결해주세요.  
   - 시작일: 2019-02-21  
   - 종료일: -  

4. Project_004:  
   - 주제: 게시판 형식 레이아웃 작성 & 간단 CSS 컨트롤 연습  
   - URL: [CSS컨트롤](https://github.com/Christianpark/COYHA-WEB/tree/master/COYHA-WEB/000_ProjectFiles/template/project_004)  
   - 내용: readMe.md를 읽고 해결해주세요.  
   - 시작일: 2019-03-07  
   - 종료일: -  
    
## 5. gitHub 사용 멤버  
- [Looksh](https://github.com/Looksh)  
- [BrokenStar](https://github.com/beteleuse06)   
- [Sunny](https://github.com/sunny5820)  
- [Gangjun-Lee](https://github.com/loveLinux06)  
- [후리미](https://github.com/gnejfekfr)  
- [이작가](https://github.com/aseon)

## 6. 함께하시는 분 (참여날짜)
19.01.23   
Chris, BrokenStar, Sunny, Looksh, 가자미, 후리미, 아옳, lovelyElla, SungBin!, GangjunLee, !dissolve  
      
19.01.30
박진현   

19.02.07  
왕회장   

19.04.02
이작가  

총원: 13명

## 나가며  
일단 재미삼아 만든 스터디입니다.  
~~이 스터디를 재밌게 하되, 진지하게 꾸준히 이어갔으면 좋겠어요....~~  
~~HTML CSS 뿐만 아니라 Javascript,PHP,JAVA 등 유연하게 다루며 언젠간 서로의 주력이 나뉠텐데 멤버들이 합심하여 서버와 클라이언트를 모두 다루고 모두가 함께 커뮤니티 사이트도 구축할 **마인드**로 해주시면 감사드리겠습니다.~~   
그렇다고, 중도 탈퇴한다고 아무도 뭐라고 안합니다! 
**일**과 **공부**를 **유연히** 나누며 진행해주시면 되요!   
~~제출기한 내에 제출하지 못하신다면 **디코에 미리 고지**해주시면 참고하겠습니다.~~  

### 모두 즐거운 코딩이 되었으면 좋겠네요.

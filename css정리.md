# css 작성방법 
## css와 hmtl 연결 방법 
    <link rel="stylesheet" href="./style.css"> : <head> 전에 작성하여 css와 html를 연결 시킨다 
## css를 통한 웹사이트 꾸미기 
### 색상 바꾸기 
    h1{color:색상;} :  h1을 "색상"의 컬러로 바꾼다 
       h1 말고 딴 html 요소의 색상 변경을 원할 시  = h1 대신 바꾸고 싶은 내용을 고르면 됨  
## 전체 적용 방법 
    *{하고 싶은 코딩} : 코딩 내용을 전체 적용
    ex) *{color: 색상;} : 전체가 "색상" 컬러로 바뀜

## div 활용법 
### div 인식
    <div>html의 코딩 내용</div> : div 안에 있는 코딩 내용을 div 전체로 인식 
### div 색상 바꾸기     
     div{ color: 색상;} : div 안에 코딩 내용들이 "색상"의 컬러로 바뀜
### div 여백(margin) 설정  
     div{ margin: 숫자px;} : 상하좌우에 모든 같은 값을 적용 시킴 
     div{ margin: 숫자1px 숫자2px;} : 숫자1 = 상하, 숫자2= 좌우의 값을 적용시킴 
     div{ margin: 숫자1px 숫자2px 숫자3px 숫자4px } : 숫자1 = 상, 숫자2= 우, 숫자3= 하, 숫자4 = 좌의 값을 적용시킴
<img src="./box.png">

### div 테두리(border) 설정  
    div{border: 숫자px solid 색상;}  : 숫자px 두께의 실선 "색상"이 생김 
### div 패딩(padding) 설정 
    div{padding: 숫자px;} : 상하좌우에 모든 같은 값 적용 
    * div margin 설정의 상하좌우 형식과 동일
### div box에 적용된 사이즈 설정 
    div{box-sizing: content-box;} : 요소 사이즈에 패딩과 테두리 포함 x
    div{box-sizing: bonrder-box;} : 요소 사이즈에 패딩과 테두리 포함 0 
    
### div 내용 설정
    div{width: 숫자px;} : 총 너비 설정
    div{margin-left: auto;   
        margin-right: auto;} : 좌우 여백 균일하게 배포
    div{margin-left: 숫자px;} : 숫자px만큼 왼쪽으로 가기    
    div{margin-right: 숫자px;} : 숫자px만큼 오른쪽으로 가기 
        
    div{float: left;}  : 내용을 맨 왼쪽으로 설정
    div{float: right;} : 내용을 맨 오른쪽으로 설정
    
## html에서 링크 연결 시 생기는 링크 효과 변경
    a {text-decoration-line: none;} : html에서 링크 연결 시 생기는 밑줄 제거
    a {text-decoration-line: underline;} : html에서 링크 연결 시 밑줄 생기게 설정 *기본값
    a {text-decoration-line: overline;} : html에서 링크 연결 시 글씨 위에 줄글 생기게 설정
    a {text-decoration-line: line-through;} : html에서 링크 연결 시 글씨 중간에 줄글 생기게 설정
    
    a:link{color: 색상;}    : 링크 연결 된 글씨 평소에 "색상"으로 적용
    a:visited{color: 색상;} : 링크 연결 된 글씨 방문 시 "색상"으로 적용
    a:hover{color: 색상;}   : 링크 연결 된 글씨 위에 마우스 시 "색상"으로 적용
    
 ## ul li 태그 가로로 배열
    ul{list-style: none;} : 목록 앞에 있는 기호들 제거 
    li{float: left;} : 가로로 정렬
<img width="200" alt="image" src="https://github.com/dkun00/likelion/assets/130130329/c3a5ef24-b089-4b01-8fc8-76791075b676">
>>
<img width="200" alt="image" src="https://github.com/dkun00/likelion/assets/130130329/9497c988-77c2-4dc4-98b6-65f8eca4b976">

 
    
 

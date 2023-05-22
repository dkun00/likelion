# html 작성방법 
## 웹페이지 만드는 코드 
    <!DOCTYPE html>
    <html lang ="ko"> : 한국어로 적기 위한 코딩 
    <head> 
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible"content="IE=edge">
    <meta name="viewport"content="width=device-width,initial-scale=1.0"> : 웹사이트 만드는 기본적인 코드 
    <title>내용</title> : 창 제목을 나타냄 
## 웹페이지 공유 시 보이는 화면 꾸미기 
    <meta property="og:title" content="내용">: 공유 시 보이는 제목 
    <meta property="og:description" content="내용"> : 공유 시 보이는 소제목
    <meta property="og:image" content="불러올 이미지 링크"> : 공유 시 보이는 이미지 

## 웹페이지에서 보이는 규칙적인 구조
    <head>    : 웹페에지에서 로그인 또는 검색 같이 젤 위에 있는 부분 
    <nav>     : 웹페이지에서의 공지나 이벤트 (1/13)이렇게 보이는 부분  
    <section> : 실질적인 웹페이지의 내용 부분 
    <footer>  : 웹페이지에서 공지사항이나 문의사항, 고객센터 있는 마지막 부분 

## 웹페이지 내용 적기 
    <h1>내용</h1> : 가장 큰 크기로 써짐 
    <h2>내용</h2> : 그 다음 크기로 써짐 
    <p>내용</p>   :  가장 기본 적인 크기로 써짐 
    <br></br>     : 내용 사이에 줄 띄우기 
    <b></b>       : 내용 강조하기(짙은 검은색으로 써짐)


## 웹페이지 글에서 링크 연결하기 
    <a href ="링크">링크 걸 내용</a> : 링크 걸 내용 클릭 시 링크로 이동 

## 웹페이지 중앙 배열
    h1{ text-align: center; }: h1 내용이 중앙배치 됨 
    * 중앙배치 하고 싶은 곳을[h1]칸에 적어  바꾸면 됨 
## 웹페이지 움직이는 배너 만들기 
    <div class="slider"></div> : div를 "sider"로 이름 변경
    <input type="radio" name="slide" id="slide1" checked>
    <input type="radio" name="slide" id="slide2"> : 라디오 버튼 영역 생성 *원하는 사진 수까지 id에 slide숫자 숫자 늘리면서 적어주면 됨 * name = 여러 옵션의 공통으로 부여해주는 이름
    <ul id="imgholder" class="imgs">밑에 코딩내용</ul> : 각 순서마다 적용할 이미지 할량
    <li><img src="이미지링크"></li> : 첫 번째에 들어갈 이미지
    <li><img src="이미지링크"></li> : 두 번째에 들어갈 이미지 *이하 원하는 수만큼 반복
    <div class="bullets"></div> : 순서 넘기는 버튼이 될 코딩 할량 
    <label for="slide1">&nbsp;</label> : 첫 번째 클릭 시 첫 번째 이미지 배너 보임 
    <label for="slide2">&nbsp;</label> : 두 번째 클릭 시 두 번째 이미지 배너 보임 *이하 코딩 넣은 사진 수만큼 반복
<img src="./banner.png" width="350px" hight="250px">    

## 웹페이지 목록 생성
    <ol><li>목록</li></ol> : 1. 목록 순으로 생성 *(1,2,3, 순서대)
    <ol type="a"><li>목록</li></ol> : a. 목록 순으로 생성 *(1,a,A,i,I 적용 가능)
    <ol start="5"><li>목록</li></ol> : 5. 목록 순으로 생성 *(특정숫자부터 순서대로 )
    <ul><li>목록<li></ul> : ⦁ 목록으로 생성
    
## 이미지 추가
    <img src="이미지링크"> : 이미지 삽입됨
    <img src="이미지링크" width=""> : 이미지 가로 크기 결정 *(% = 브라우저 창의 크기 단위, px = 픽셀단위)
    <img src="이미지링크"> : 이미지 세로 크기 결정 *(% = 브라우저 창의 크기 단위, px = 픽셀단위)
    
 
    
    



## css_pure_parallax
# CSS의 단위
px : 브라우저에서 쓰는 기본 단위로 고정적이다.
     브라우저의 폰트는 기본적으로 16px을 사용한다.
     모바일에서도 16px을 기본 단위로 사용한다.
     하지만 사용자가 폰트 크기를 변경하는 경우도 있으므로 html태그에 기본적으로 지정하는것이 좋다.

em: 가변적인 폰트로, 부모가 가지고 있는 폰트 사이즈로 부터 상속 받는다.
rem: 가변적인 폰트로 Root의 폰트 사이즈를 상속 받는다.

vw: 뷰포트의 width값의 percentage 값

vh: 뷰포트의 height값의 percentage 값

%: 부모가 가지고 있는 크기의 상대적인 percentage값

# background의 속성
    background-image:url(이미지주소);
    background-position:가로시작점 세로시작점;
    background-attachment:fixed(scroll);
    background-size:cover(contain); cover는 긴쪽을 contain은 작은쪽을 기준으로 화면에 맞춘다.
    background-repeat:repeat(no-repeat,repeat-X 등등 스스로 찾아볼것)

# ::after ::before 가상클래스

객체에 앞뒤에 생성되는 가상클래스 display:inline 이기때문에 display변경후 그래픽 요소로 추가할 수 있다.       

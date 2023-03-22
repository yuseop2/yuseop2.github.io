# CSS속성
## CSS 폰트 관련 속성 
웹 폰트 : 구글 웹폰트 또는 눈누, 응용프로그램용 폰트 : 다폰트
font-family:"1차폰트명", 2차폰트명, 3차폰트명;
3차 폰트는 기본 폰트를 적용함
기본폰트 : 브라우저에서 기본적으로 제공하는 폰트
(sans-serif(고딕), serif(명조), cursive(궁서), monospace(가로세로비율1:1), fantasy(심볼기호나 디자인포트))

## CSS 크기 관련 속성
margin : 테두리의 바깥여백 / 통합속성
margin:10px; 상/우/하/좌 모두 10px
margin:10px 20px; 상/하 10px 좌우 20px

선택자 { width:400px; margin:10px auto;} 크기400px 박스를 좌우 가운데로 배치하는법
세부속성 : margin-top/margin-bootom/margin-left (순서는 통합먼저)
padding : 테두리의 안쪽여백

box-sizing:
content-box 크기 : 크기+패딩+보더+마진
border-box 크기 : 크기+마진 (나머지 패딩,보더는 width,heigth에 들어가서 포함됨)

### 위치 속성 position  //중요파트!!
static - 정적. 기본값 -margin으로
relative - 상대적인 위치설정 - 기존거 기준 - Top,Left로 하지말고 margin으로 해라 그래야 안헷갈림
absolute - 절대적 - (0,0)기준 -top/left로
fixed - 고정. (relative와 같을수도있지만) 화면에 고정이라 스크롤 내려도 같은자리에 있음 -top/left로

### 레이어 속성
z-index : 어느층을 위로 올려서 보이게 할지(숫자 큰게 보임)

### 흐름 속성
float : left|right|both|none
position이 static 이거나  relative일 경우 활용

### 흐름 해제 속성
float left의 경우 clear left
보통 clear both

### CSS 가시 속성
disply : inline | block | in-line block | none
inline  - 위아래 마진 패딩 설정 불능
        - img,video 
        - input,span,strong,em 다 불가능
block   - 크기지정 가능
        - h,p,ul,ol,dl,li,dt,dd,div,section 등
        - 만약, 인라인 요소를 블록 변경시에 활용 ( displaay-block ㄱㄱ하면 됨)
inline-block : 한 줄 안에 배치도 가능, 위아래 마진 패딩 가능, 크기지정가능        -    
none - 출력 안할경우 사용

### 불투명도
opacity 0~1

### 가시 속성
visibility - visible | hidden
display -none 이랑은 다르다 hidden을 하면 안보이는것뿐, 존재한다.

### 넘침 속성
overflow : hidden | visible | scroll (스크롤바 무조건 생김) | auto (사이즈 클때만 스크롤바 생김) 


split icon : 하나의 아이콘셋 이미지를 쪼개어 여러 아이콘을 표시 
        background-image는 같고, background-position으로 조절하여 해당 아이콘이 나타나도록 함













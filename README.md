# Noto-sans-CJK-Diet version::1.0.0

Noto-sans 파일은 일명,본고딕 폰트입니다.
- 구글 웹폰트에서 배포되는 본고딕 폰트의 용량 -> 115.2 MB
- 다이어트된 용량 -> 17.4 MB

#### 구글 웹폰트 사용안하고 왜 이걸써야돼?
>> 구글 웹폰트는 정말 느립니다. 차라리 로컬에서 불러오는게 더 빠릅니다.

### 이 폰트는 어떻게 적용시켜야돼?
- css버전
    1. 다운을 받고, 원하는 경로에 넣습니다.
    2. 기존에 css에 기록했던 파일 맨위에 @import('noto-sans-scott.css'); 적어놓습니다.
    3. 적용시키고자 하는 스타일에 font-family:'noto-sans-scott', "Helvetica Neue",Helvetica,Arial,sans-serif; 를 적습니다.
- sass버전
    1. 다운을 받고, 원하는 경로에 넣습니다.
    2. 기존 sass의 메인파일 (보통 style.scss) 파일에 이 두가지를 기록해서 넣습니다.
        - @import '/noto-sans-scott/scss/noto-sans-scott'; -> noto-sans-scott.scss 파일 경로 추가
        - $noto-sans-scott-dir-path: "/bower_components/noto-sans-scott/fonts"; -> fonts 파일의 경로 추가


### 'font-weight'가 어떻게 되?
- font-weight : 100 -> Thin,
- font-weight : 200 -> Light,
- font-weight : 300 -> DemiLight,
- font-weight : 400 -> Regular,
- font-weight : 500 -> Medium,
- font-weight : 700 -> Black,
- font-weight : 900 -> Bold


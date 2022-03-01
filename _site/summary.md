- 서버 열기     
bundle install 
bundle exec jekyll serve --trace


- site.title, site.author....   
-> _config.yml의 데이터를 지칭한다

- relative_url  
 -> 자기 자신 말함

- md >>> html (우선순위)

- page.background , page.title...   -> md 파일 맨 위에 적혀 있는 것(레이아웃이 page일 때만)

- paginate_path를 고쳐줘야 페이지 등장

# css
1. nav
 - nav-item : li의 클래스, 글꼴,크기 등
 - nav-link : a의 클래스, 링크 밑줄 없애기 등
 
2. background
 - background-color
 - background-repeat : 수직이나 수평으로 반복되게 나타날 수 있음(no-repeat) 
 - background-position : 상대 위치 설정 (center center)
 - background-attachment : 이미지를 고정, 스크롤에 따라 이동 등 설정 (scroll)
 - background : 여러 속성을 한번에 설정
 - background-size : 크기 (cover : 이미지의 크기가 요소보다 크다는 조건하에 이미지를 작게 조정,비율 유지, contain : 이미지의 크기가 요소보다 작다는 조건하에 이미지를 크게 조정,비율유지)

# class
col-lg-7 col-md-10 mx-auto
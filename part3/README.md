### Doctype?
>![](https://images.velog.io/images/dlfehd54/post/cfbcae7c-428d-434a-84d3-3a1541ed53be/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202021-03-03%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%208.35.46.png)

### html 태그

> ```html
> <html>  </html>
>```
>문서의 전체 범위
>: HTML문서가 어디에서 시작하고 어디에서 끝나는지 알려주는 역할

### head 태그
> ```html
><head> </head>
>```
>문서의 정보를 나타내는 범위
>:웹 페이지의 보이지 않는 정보를 작성(제목, 설명, css등)

### body 태그
> ``` html
><body> </body>
>```
>문서의 구조를 나타내는 범위
>: 웹 페이지에 보여지는 구조를 작성

### link태그
>```
><link rel=""href=""/>
>```
>rel(relationship) : 가져올 문서와의 관계
>
>href : 문서 경로
>#### ex
>
>```
><link rel="stylesheet" href="./index.css"/>
><link rel="icon" href="./favicon.png">
>```
> 
>- link태그는 닫는 태그가 없어서 빈태그라고 불림.  
>보통 빈 태그들은 <~/>형식으로 써주는게 더 안정성이 높다.
>
>![](https://images.velog.io/images/dlfehd54/post/879c1799-02a2-4899-824d-e05c9763e5b0/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202021-03-03%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%209.12.57.png)
>* naver 앞 로고를 favicon이라고 함.

### img태그
>```
><img src="" alt="">
>```
>src : 파일 경로
>
>alt(Alternate) : 이미지가 출력되지 못하는 경우 출력할 텍스트)

### 상대, 절대 경로
>![](../md_image/1.png)
>#### ex)
>```
>상대경로
> <img src="./images/1.jpeg" alt="error">
> <img src="images/1.jpeg" alt="error">
>절대경로
> <img src="/part3/images/1.jpeg" alt="error">
>```

#### 출처
- 패스트캠퍼스(HEROPY님 강의)
- 위키백과

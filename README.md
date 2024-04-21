# 부스트코스 웹개발프로그래밍(풀스택)


# 목차
- [프로젝트 소개](#🖥️-프로젝트-소개)
- [학습일지](#학습일지-목차로-이동)
    - [마크다운 (Markdown)](#마크다운-markdown)
***

# 🖥️ 프로젝트 소개 [(목차로 이동)](#목차)
부스트코스의 웹 프로그래밍(풀스택) 강좌 따라가기 + 응용하기
<br>

### 🕰️ 개발 기간
* 24.04.21일 - 24.04.??일

### 🧑‍🤝‍🧑 맴버구성
 - 팀장  : 정진용 - 학습일지 작성, 모든 시행착오 겪기, 조바심 내지 말고 하나씩 제대로 정리하고 활용하기
 - 팀원1 : 정진용 - 팀장 다독이기, 가끔 팀장 데리고 나가서 걷기

### ⚙️ 개발 환경
- `Java 8`
- `JDK 1.8.0`
- **IDE** : STS 3.9
- **Framework** : Springboot(2.x)
- **Database** : Oracle DB(11xe)
- **ORM** : Mybatis

<!-- ## 📌 주요 기능
#### 로그인 - <a href="https://github.com/chaehyuenwoo/SpringBoot-Project-MEGABOX/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C(Login)" >상세보기 - WIKI 이동</a>
- DB값 검증
- ID찾기, PW찾기
- 로그인 시 쿠키(Cookie) 및 세션(Session) 생성
#### 회원가입 - <a href="https://github.com/chaehyuenwoo/SpringBoot-Project-MEGABOX/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C(Member)" >상세보기 - WIKI 이동</a>
- 주소 API 연동
- ID 중복 체크
#### 마이 페이지 - <a href="https://github.com/chaehyuenwoo/SpringBoot-Project-MEGABOX/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C(Member)" >상세보기 - WIKI 이동</a>
- 주소 API 연동
- 회원정보 변경

#### 영화 예매 - <a href="https://github.com/chaehyuenwoo/SpringBoot-Project-MEGABOX/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C(%EC%98%81%ED%99%94-%EC%98%88%EB%A7%A4)" >상세보기 - WIKI 이동</a>
- 영화 선택(날짜 지정)
- 영화관 선택(대분류/소분류 선택) 및 시간 선택
- 좌석 선택
- 결제 페이지
- 예매 완료
#### 메인 페이지 - <a href="https://github.com/chaehyuenwoo/SpringBoot-Project-MEGABOX/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C(%EB%A9%94%EC%9D%B8-Page)" >상세보기 - WIKI 이동</a>
- YouTube API 연동
- 메인 포스터(영화) 이미지 슬라이드(CSS)
#### 1대1문의 및 공지사항 - <a href="" >상세보기 - WIKI 이동</a> 
- 글 작성, 읽기, 수정, 삭제(CRUD)

#### 관리자 페이지 
- 영화관 추가(대분류, 소분류)
- 영화 추가(상영시간 및 상영관 설정) -->



# 학습일지 [(목차로 이동)](#목차)

## 마크다운 (Markdown) [(목차로 이동)](#목차)
본격적인 개발에 앞서, 내가 배우는 것을 github에 한 눈에 정리하기 위해, 마크다운을 공부하자!

### 헤더 (Header)
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

* H7부터는 존재하지 않음
```

***
### 줄 바꾸기 (LF, Line Feed)
Enter 두 번 눌러서 빈 줄(Blank) 추가하기

혹은
```
<br>
<br/>
<br />
```

***
### 순서있는 목록 (Ordered list)
```
1. 첫 번째 항목
2. 두 번째 항목
3. 세 번째 항목

1) 첫 번째 항목
2) 두 번째 항목
3) 세 번째 항목

1. 1단계
    1. 2단계
        1) 3단계
            1) 4단계
```

***
### 순서없는 목록 (Unordered list)
*, +, - 로 사용 가능하다. 섞어 쓰는 것도 가능하다.
```
* 빨강
  * 녹색
    * 파랑

+ 빨강
  + 녹색
    + 파랑

- 빨강
  - 녹색
    - 파랑

* 1단계
  - 2단계
    + 3단계
      + 4단계
```

***
### 구분선 (Division Line)
```
---
***

* 더 많이 사용해도 되고, 띄어쓰기를 인식하지 않음.
ex)
----
***** ** ***
```

***
### 코드 블럭
블록 위아래로 ```(물결표 버튼) 붙이기

GitHub 에서는 코드블럭코드("```") 시작점에 사용하는 언어를 선언하여 문법강조(Syntax highlighting)이 가능하다.

    ```
    library(tidyverse)
    df %>% filter(tmax >= 25)
    ```

    ```R
    library(tidyverse)
    df %>% filter(tmax >= 25)
    ```


들여쓰기(tab) 혹은 4칸 띄어쓰기
```
    library(tidyverse)
    df %>% filter(tmax >= 25)
```

***
### 하이퍼링크 (Hyperlink)
```
<이동할 주소>

[보여지는 텍스트](이동할 주소)

ex)
<https://www.google.co.kr/>

[구글로 이동](https://www.google.co.kr/)
```

***
### 목차 이동
```
# 이동할 위치

[보여지는 텍스트](#이동할-위치)


* 헤더에 특수문자가 포함될 경우, 이를 무시하고 작성한다.
ex)
# 열심히 해야지!!! (아님)  ====> (#열심히-해야지-아님)
```

***
### 주석

```
<!-- 주석 내용 -->

* VScode 단축키: Ctrl + /
```

***
### 강조
```
*single asterisks* // 기울임체
_single underscores_ // 기울임체
**double asterisks** // 볼드체
__double underscores__ // 볼드체
~~cancelline~~ // 취소선
```

***
### 이미지
```
![대체 텍스트(alt)](이미지_소스_경로 "이미지 설명(title)")

ex)
![HTML 짤이었던 것](유효하지-않은-경로 "HTML 짤")

![HTML 짤이었던 것](./HTML%20짤.webp "HTML 짤")
```
![HTML 짤이었던 것](유효하지-않은-경로 "HTML 짤")

![HTML 짤이었던 것](./HTML%20짤.webp "HTML 짤")


***


## ?? (??) [(목차로 이동)](#목차)
??
















***
***
***

# 문서의 끝! [(목차로 이동)](#목차)
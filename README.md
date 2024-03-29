# 제목(Header)

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks): 2번 띄어쓰기(안먹히면 br태그 사용)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼처리 화려 강산  
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
   1. 순서가 필요한 목록(들여쓰기 2번)
   1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links) -> [이름](url)

[Google](https://google.com)

[Naver](https://nvaer.com "NAVER로 이동!") // title적용

# 이미지(Image)

![대체텍스트](url)
[![대체텍스트](url)](url)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>
> > 중첩된 인용문
> >
> > > 중중첩된 인용문1

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="">NAVER</a>
```

# 표(Table)

position 속성

| 값       |       의미        | 기본값 |
| -------- | :---------------: | -----: |
| static   |     기준 없음     |      O |
| relatvie |     요소 자신     |      X |
| absolute | 위치 상 부모 요소 |      X |
| fixed    |      뷰포트       |      X |

기본은 왼쪽 정렬  
:--: -> 가운데 정렬  
--: -> 오른쪽 정렬

# 원시 HTML(Raw HTML)

## 마크다운에서 지원하지 않는 속성을 쓰기위해 원시 HTML 사용

밑줄 사용하기 -> u태그 혹은 text-decoration css 속성

동해물과 <u>백두산</u>이 마르고 닳도록<br />
하느님이 보우하사 우리나라 만세

동해물과 <span style="text-decoration:underline">백두산</span>이 마르고 닳도록<br />
하느님이 보우하사 우리나라 만세

# 수평선(Horizontal Rule)

---

---

---

<마크다운>  
=> 문법이 쉽고 간결, 관리가 쉬움, 지원가능한 플랫폼과 프로그램이 다양함  
=> 표준이 없으므로 모든 HTML 마크업을 대신하지 못함  
=> 파일생성시 README.md 로입력 => github 에 마크다운파일을 찾도록 설정되어있기 때문에

#제목 (Header)

# 제목 1
## 제목 2
### 제목 3

# 문장 (Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈 (Line Breaks)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산  
대한 사랑 대한으로 길이 보전하세

=> 문장에서 줄바꿈처리 할때는 띄어쓰기를 두번쓰면 줄바꿈 처리가 되어 다음줄에 문장이 시작됨 ( br 태그 사용해서 강제줄바꿈 처리도 가능함)

# 강조

_이텔릭_  
**두껍게**  
~~취소선~~  
<u>밑줄</u>  


# 목록

1. 순서가 필요한 목록  
1. 순서가 필요한 목록  
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록 
1. 순서가 필요한 목록

- 순서가 필요한 목록
- 순서가 필요한 목록
- 순서가 필요한 목록
- 순서가 필요한 목록

# 링크 (Links)
<a href="https://google.com"> GOOGLE </a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동!"> NAVER </a>

[NAVER](https://naver.com "NAVER로 이동!")


# 이미지 (Images)

![HEROPY](https://heropy.blog/css/images/logo.png)

=> 링크 앞에 !입력하면 이미지가 보여짐   
`![]()` 순으로 작성

# 인용문 (BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.   
> (네이버 국어 사전)

> 인용문1
>> 중첩된 인용문2
>>> 중중첩된 인용문3


# 인라인 (Inline) 코드 강조

css에서 `background` 혹은 
`background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다. 

# 블럭 (block) 코드 강조

```html
<a href="https://google.com" target="_blank"> GOOGLE </a>
```
=> 코드에 하이라이트 효과를 주어 강조할 수 있음 (자바스크립트,css,터미널에 입력하던 명령문도 입력 가능)


# 표 (Table)

position 속성

값 | 의미 | 기본값  
:--|:--:|--:
static | 기준 없음 | O  
relative | 요소 자신 | X   
absolute | 위치 상 부모 요소 | X  

=> 글의 정렬을 바꾸고 싶을 경우,   가운데 정렬 기호 양 옆에 ::  
오른쪽 정렬 기호 맨 끝에 :  
왼쪽 정렬 기호 맨 앞에 :


# 원시 HTML (Raw HTML)

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br>
하느님이 보우하사 우리나라 만세

=> 위와 같이 실제 HTML 문법을 사용하는 방법


# 수평선 (Horizaontal Rule)

---

***

___

=> -,*,_ 기호를 사용하여 수평선을 만들 수 있음
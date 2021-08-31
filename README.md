# 제목(Header)
>**앞에 #을 붙여주면 제목같이 사용할 수 있다.**

```plaintext
# 제목(Header)
``` 

***

>**앞에 #의 갯수 만큼 붙여주면 h태그와 같이 강조 한다.**
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

```plaintext
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
```

  
  
# 문장(Paragraph)

>**단순 문장은 그대로 적으면 된다.**

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 줄바꿈 (Line Breaks)

>**줄 바꿈은 띄어쓰기 두번 또는 br 태그를 사용한다.** 

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한사람 대한으로 길이 보전하세  

```plaintext
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세<br/>
무궁화 삼천리 화려 강산
```


# 강조(Emphasis)

_이텔릭체_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>
```plaintext
_이텔릭체_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~ 
<u>밑줄</u>
```

# 목록(List) 
>**목록 안에 목록은 띄어쓰기 4번**
1. 순서가 필요한 목록  
1. 순서가 필요한 목록  
1. 순서가 필요한 목록  
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록  
1. 순서가 필요한 목록  

- 순서가 필요하지 않은 목록  
- 순서가 필요하지 않은 목록  
- 순서가 필요하지 않은 목록  
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록  
```plaintext
1. 순서가 필요한 목록  
1. 순서가 필요한 목록  
1. 순서가 필요한 목록  
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록    
1. 순서가 필요한 목록  

- 순서가 필요하지 않은 목록  
- 순서가 필요하지 않은 목록  
- 순서가 필요하지 않은 목록  
    - 순서가 필요하지 않은 목록 
    - 순서가 필요하지 않은 목록 
- 순서가 필요하지 않은 목록
```


# 링크(Links)

[GOOGLE](https://google.com)
```plaintext
[GOOGLE](https://google.com)
```
**타이틀이 있는 링크**
<a href="https://naver.com" title="NAVER로 이동" target="_blank">NAVER</a>  

```plaintext
[NAVER](https://naver.com "NAVER로 이동") 
```


# 이미지(Image)
**이미지 삽입**
![Kakao](https://t1.kakaocdn.net/friends/new_store/prod/main_tab/feed/npc_20210429161651.png)

```plaintext
![Kakao](https://t1.kakaocdn.net/friends/new_store/prod/main_tab/feed/npc_20210429161651.png)
```
**링크 이미지 삽입**
[![Kakao](https://t1.kakaocdn.net/friends/new_store/prod/main_tab/feed/npc_20210429161651.png)](https://store.kakaofriends.com/kr/profile/17?tab=story)

```plaintext
[![Kakao](https://t1.kakaocdn.net/friends/new_store/prod/main_tab/feed/npc_20210429161651.png)](https://store.kakaofriends.com/kr/profile/17?tab=story)
```

# 인용문 (BlockQuote)

> 남의 글이나 말에서 따 온 문장.   
> (네이버 국어사전)  

```plaintext
> 남의 글이나 말에서 따 온 문장.   
> (네이버 국어사전)  
```
***


**중첩 인용문**
> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문1
>>> 중중첩된 인용문2
>>> 중중첩된 인용문3
```plaintext
> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문1
>>> 중중첩된 인용문2
>>> 중중첩된 인용문3
```


# 인라인(inline) 코드 강조

>**코드를 강조하고 싶을 때.**

ex) css에서 `background` 혹은 `background-image` 속성으로 요소에 배경이미지를 삽일 할 수 있습니다.

```plaintext
css에서 `background` 혹은 `background-image` 속성으로 요소에 배경이미지를 삽일 할 수 있습니다
```


# 블록(block) 코드 강조

코드의 앞 뒤에 ```를 입력  
>**HTML**
```html
<a href="https://google.com" title="NAVER로 이동">GOOGLE</a>
```

```plaintext
```html
<a href="https://google.com" title="NAVER로 이동">GOOGLE</a>   ```
```

***

>**CSS**
```css
.list li {
    width: 500px;
    height: 300px;
    font-size: 20px;
}
```

```plaintext
```css
.list li {
    width: 500px;
    height: 300px;
    font-size: 20px;
}
```


***
>**JAVASCRIPT**
```javascript 
function func() {
    var a = 'AAA';
    return a;
}
```

```plaintext
```javascript 
function func() {
    var a = 'AAA';
    return a;
}```

```

***
>**Terminal**
```bash
$ git commit -m 'Study Markdown'
```

```plaintext
```bash
$ git commit -m 'Study Markdown'  ```
```


***
>**단순 블록코드 강조**
```plaintext
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세
```

```plaintext
```plaintext
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  ```
```
# 표(Table)
>:위치는 글자 정렬 위치
ex) position 속성

값 | 의미 | 기본값  
--|:--:|--:|  
static | 기준 없음 | 0
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

```plaintext
값 | 의미 | 기본값  
--|:--:|--:| 
static | 기준 없음 | 0
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X
```

# 원시 HTML(Raw HTML)
>html 태그 처럼 내부 스타일링을 할 수있다. 


동해물과 <span style="text-decoration: underline;">백두산이</span> 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세
```plaintext
동해물과 <span style="text-decoration: underline;">백두산이</span> 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세
```

***

<a href="https://naver.com" title="NAVER로 이동" target="_blank">NAVER</a> 
```plaintext
<a href="https://naver.com" title="NAVER로 이동" target="_blank">NAVER</a> 
```

***
<img width="70" src="https://t1.kakaocdn.net/friends/new_store/prod/main_tab/feed/npc_20210429161651.png" alt="
kakao">

```plaintext
<img width="70" src="https://t1.kakaocdn.net/friends/new_store/prod/main_tab/feed/npc_20210429161651.png" alt="
kakao">
```


# 수평선(Horixontal Rule)
>수평을 표시하는 세가지
---

```plaintext
---
***
___
```

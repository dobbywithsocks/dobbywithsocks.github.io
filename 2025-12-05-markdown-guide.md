---
layout: single
title: "Markdown 문법"
---
# 소개
기본적으로 Jekyll을 이용해 포스트를 작성하려면 Markdown 문법에 익숙해져야 한다. Markdown은 2004년에 John Gruber에 의해 개발된 언어이다. 비교적 단순한 기호 및 글자로 손쉽게 직관적으로 문서를 작성하고 읽을 수 있는 것이 특징이다. 좀 더 자세한 설명은 아래 사이트들을 참고하면 좋을듯 하다.   
[ihoneymon 님의 글](https://gist.github.com/ihoneymon/652be052a0727ad59601#file-how-to-write-by-markdown-md)   
[Markdown Guide (English)](https://www.markdownguide.org/)

# 헤더
    # H1
    ## H2
    ### H3
    #### H4
    ##### H5
    ###### H6

*주석: 높은 숫자는 더 높은 수준의 헤더를 의미한다.*
# 코드 블럭
* 4개의 공백 또는 하나의 탭으로 들여쓰기를 만나면 변환되기 시작해 들여쓰지 않은 행을 만날 때까지 코드 블럭을 유지한다.
* 또는 코드 블럭 코드 ("```")를 코드 앞뒤로 붙여준다.

# Blockquote
    > First blockquote
    >   > Second blockquote
    >   >   > Third blockquote

# 목록

### 숫자 목록
    1. First
    2. Second
    3. Third

### bullet point 목록
    * apple
        * banana
            * coconut
    + apple
        + banana
            + coconut
    - apple
        - banana
            - coconut

세 가지 기호 모두 동일한 방식의 bullet point를 만들어낸다.

    * apple
        + banana
            - coconut
                + donkey

서로 섞어서도 사용할 수 있다.

# 수평선
```
* * *
***
*****
- - -
--------------------------------
```
위 모두 수평선을 만들 수 있다.

# 강조
```
*single asterisks*, _single underscores_: italic
**double asterisks**, __double underscores__: bold
~~cancel line~~
```
# 이미지
```
![Alt text](/path/to/image.jpg)
![Alt text](/path/to/image.jpg "Image Title")
```
사이즈 조절은 ```<image width="" height=""></img>```를 이용한다.
```
<img src="/path/to/image.jpg" width="450px" height="300px" title="px 크기 설정" alt="이건 뭐지"></img><br/>
<img src="/path/to/image.jpg" width="40%" height="30%" title="비율 크기 설정" alt="이건 뭐지"></img>
```

# 줄바꿈
3칸 이상 띄어쓰기를 하면 줄이 바뀐다.

# 수정할 것
각각 예시를 붙여넣어 이해를 도울 수 있을 것 같다.
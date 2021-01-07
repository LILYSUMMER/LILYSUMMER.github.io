# LILYSUMMER.github.io

# 마크다운(Markdown)

> 일반 텍스트 형식 구문을 사용하는 마크업 언어의 일종으로 사용법이 쉽고 간결하여 빠르게 문서 정리를 할 수 있습니다. 단, 모든 HTML 마크업을 대체하지는 않습니다

## 1. 문법

## 1.1 Header

> 헤더는 제목을 표현할 때 사용합니다. 단순히 글자의 크기를 표현하는 것이 아닌 의미론적인 중요도를 나타냅니다. 
* `<h1>`부터 `<h6>` 까지 표현이 가능합니다. 
* `<#>` 의  개수로 표현하거나 `<h1></h1>` 의 형태로 표현이 가능합니다.

# h1 태그입니다.
## h2 태그입니다.
### h3 태그입니다.
#### h4 태그입니다.
##### h5 태그입니다. 
###### h6 태그입니다.
  
## 1.2 List
> 목록을 나열할 때 사용합니다. 순서가 필요한 항목과 그렇지 않은 항목으로 구분할 수 있습니다. 순서가 있는 항목 아래 순서가 없는 항목을 지정할 수 있으며 그 반대도 가능합니다 

* 순서가 있는 목록
  - `1.`을 누르고 스페이스바를 누르면 생성할 수 있습니다. 
  - `tap` 키를 눌러서 하위항목을 생성할 수 있고 `shift + tab` 키를 눌러서 상위 항목으로 이동 할 수 있습니다. 

* 순서가 없는 목록 
  - `-`(하이픈)을 쓰고 스페이스바를 누르면 생성할 수 있습니다.
  - `tab` 키를 눌러서 하위 항목을 생성할 수 있고 `shift + tab` 키를 눌러서 상위 항목으로 이동 할 수 있습니다. 

1. 순서가 있는 항목 
2. 순서가 있는 항목  
  1. 순서가 있는 하위 항목
  2. 순서가 있는 하위 항목
  
* 순서가 없는 항목
* 순서가 없는 항목 
  * 순서가 없는 하위 항목
  * 순서가 없는 하위 항목

## 1.3 Code Block
> 코드 블럭은 작성한 코드를 정리하거나 강조하고 싶은 부분을 나타낼 때 사용합니다. 인라인과 블럭 단위로 구분 할 수 있습니다. 

* Inline 
  * 인라인 블럭으로 처리하고 싶은 부분을 `(백틱) 으로 감싸줍니다.
* Block 
  * `(백틱)을 3번 입력하고 ```enter```를 눌러 생성합니다.

`add` 한 요소를 remote 저장소에 올리려면 `$ git push origin master` 를 터미널에 입력합니다. 

```
$ git add .
$ git commit -m "first commit"
$ git push origin master
```

## 1.4 Image

> 로컬에 있는 이미지를 삽입하거나 이미지 링크를 활용하여 이미지를 나타낼 때 사용합니다.

* `![]()` 을 작성하고 `()` 안에 이미지 주소를 입력합니다. `[]`안에는 이미지 파일의 이름을 작성합니다.
* 로컬에 이미지파일을 저장한 경우는 절대 경로가 아닌 상대 경로를 사용하여 이미지를 저장합니다.

![Git_logo_2-color.png](https://image.librewiki.net/1/1d/Git_logo_2-color.png)


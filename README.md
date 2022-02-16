# Markdown 101  

## **Markdown**,

<p align=center>
Markdown은 사용되는 환경에 따라 사용자에게 다르게 보여질 수 있으며, 문법의 표준이 없는 단점이 있으므로, 문서를 꾸미는 용도로는 부적절합니다.   
쉽게 작성할 수 있고, 쉽게 수정할 수 있는 가벼운 언어라는 점을 비춰볼 때 
메뉴얼을 작성하기 위한 간단한 문서작업에 사용하는 것이 좋을 것이라 생각됩니다.
</p>
<br>
<br>

## **1. 제목(Title)**
HTML의 `<h1> ~ <h6>` 태그의 기능을 대체합니다.

```Markdown
  # Title1 - H1 
  ## Title2 - H2
  ### Title3 - H3
  #### Title4 - H4
  ##### Title5 - H5
  ###### Title6 - H6

```
**위 코드의 실행결과**
<br>

   # Title1 - H1 
  ## Title2 - H2
  ### Title3 - H3
  #### Title4 - H4
  ##### Title5 - H5
  ###### Title6 - H6  

<br/>
<br/>
<br/>

## 2. **목록(List)**
순서가 있는 리스트의 경우 HTML의 `<ol><li></li><ol>`태그를,  
순서가 없는 리스트의 경우에는 HTML의 `<ul><li></li></ul>`태그의 역할을 합니다.

**오늘 할 일 (순서가 있는 리스트)**
```Markdown
1. 강아지 산책시키기.
2. 마트가서 반찬거리 사기. 
3. 도서관에서 대출한 책 반납하기
1. 주간 공부 계획 세우기. // **인덱스가 순서에 맞게 부여됩니다.**

```
<br>

**위 코드의 실행결과**
<br>

1. 강아지 산책시키기.
2. 마트가서 반찬거리 사기. 
3. 도서관에서 대출한 책 반납하기
1. 주간 공부 계획 세우기. // **인덱스가 순서에 맞게 부여됩니다.**
<br>
<br>

**장바구니에 담은 책 (순서가 없는 리스트)**
```Markdown
// 세가지 기호(-,+,*) 중 어떤 것을 무엇이든 사용해도 됩니다.
// 세가지 기호는 기호가 사용되는 환경마다 차이가 있니 일관성있게 사용하는 것이 좋습니다.
- 이기적 유전자
- 설국
+ 변신
* 수레바퀴 밑에서 
```
<br>

**위 코드의 실행결과**
<br>
- 이기적 유전자
- 설국
+ 변신
* 수레바퀴 밑에서

<br/>
<br/>
<br/>

## 2. **강조(Emphasis)**
HTML의 `<em> <strong> <del>`태그의 기능을 대체합니다.
```Markdown
  *이텔릭체 (single asterisks)*
  _이텔릭체 (single underscores)_
  **볼드체 (double asterisks)**
  __볼드체 (double underscores)__
  ~~취소선(cancelline)~~
  <u>밑줄(underline)</u>

// 각 기호들을 조합하여 사용할 수도 있습니다. 
  **~~볼드체+취소선~~**
  ___볼드체+이텔릭체___
```
<br>

**위 코드의 실행결과**
<br>

  *이텔릭체 (single asterisks)*  
  _이텔릭체 (single underscores)_  
  **볼드체 (double asterisks)**  
  __볼드체 (double underscores)__  
  ~~취소선(cancelline)~~  
  <u>밑줄(underline)</u>

// 각 기호들을 조합하여 사용할 수도 있습니다.   
  **~~볼드체+취소선~~**  
  ___볼드체+이텔릭체___

<br/>
<br/>
<br/>

## 3. 주소(Link)
HTML의 `<a>`태그의 기능을 대체합니다.


```Markdown
// [text](link)의 형태로 작성합니다.

[GOOGLE](https://google.com)

[NAVER](https://naver.com "NAVER 바로가기")

[상대경로](../user/info)

// [text]:[variable]로 작성하여 할당된 url를 사용할 수 있습니다.
[Github][github]

// url 할당하기
[github]:https://github.com/Jihoyang0120
```
<br>

**위 코드의 실행결과**
<br>

[GOOGLE](https://google.com)

[NAVER](https://naver.com "NAVER 바로가기")

[상대경로](../user/info)

[Github][github]

[link]:https://github.com/Jihoyang0120/Markdown-editing
[github]:https://github.com/Jihoyang0120

<br/>
<br/>
<br/>

## 4. 이미지(Image)
HTML의 `<img>`태그의 기능을 대체합니다.

```Markdown
// ![text](imageLink)의 형태로 작성합니다.   

**강아지 사진**
![Dog](https://avatars.githubusercontent.com/u/90703346?v=4)

// 주소와 똑같이 이미지의 url주소도 변수에 할당할 수 있습니다. 
**고양이 사진**(클릭시 링크 이동!)
[![catImage][cat]](https://www.cosmopolitan.com/lifestyle/a29538844/popular-cat-names/)


[cat]:https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/close-up-of-cat-wearing-sunglasses-while-sitting-royalty-free-image-1571755145.jpg?crop=0.670xw:1.00xh;0.147xw,0&resize=980:*
```
<br>

**위 코드의 실행결과**
<br>
<br>

**강아지 사진**  
![Dog](https://avatars.githubusercontent.com/u/90703346?v=4)


**고양이 사진** (클릭시 링크 이동!)  
[![catImage][cat]](https://www.cosmopolitan.com/lifestyle/a29538844/popular-cat-names/)


[cat]:https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/close-up-of-cat-wearing-sunglasses-while-sitting-royalty-free-image-1571755145.jpg?crop=0.670xw:1.00xh;0.147xw,0&resize=980:*

<br>
<br>
<br>
<br>

## 5. 코드(Code)
HTML의 `<pre>`, `<code>`로 변환되며,   
`Grave(``)`를 통해서 입력할 수 있습니다.

### **in-line 코드 표현**
Grave문자를 활용하여 본문의 코드를 강조할 수 있습니다.
<br>
<br>

```Markdown
Tabbnabbing이란, `target="_blank"`에 의해 열린 새 페이지에서 `window.opener.location`을 변경하여, 기존 페이지를 피싱 페이지로 변경해 사용자 정보를 탈취하는 것입니다. 이러한 피싱이 가능한 이유는 기본적으로 새 탭을 열면 현재 탭을 열었던 탭의 참조를 반환하기 때문입니다. 이 참조를 없애는 방법이 바로 `rel="noreferrer noopener"`를 추가하는 것입니다. 
```
<br>

**위 코드의 실행결과**
<br>
<br>


Tabbnabbing이란, `target="_blank"`에 의해 열린 새 페이지에서 `window.opener.location`을 변경하여, 기존 페이지를 피싱 페이지로 변경해 사용자 정보를 탈취하는 것입니다. 이러한 피싱이 가능한 이유는 기본적으로 새 탭을 열면 현재 탭을 열었던 탭의 참조를 반환하기 때문입니다. 이 참조를 없애는 방법이 바로 `rel="noreferrer noopener"`를 추가하는 것입니다. 

<br>
<br>

### **Block 코드 표현**
3번의 연속된 Grave를 활용하여 블록 단위의 코드를 표현할 수 있습니다.  
Grave 뒤에 블록에 쓰일 언어를 작성함으로써, 언어별로 보여지는 블록의 코드를 스타일을 바꿀 수 있습니다.

```python
# Python deep copy
import copy
a = [[1,2],[3,4]]
b = copy.deecopy(a)
a[1].append(5)
```

```javascript
// Javascript deep copy
const obj1 = {
  a: 1,
  b: "string",
  c: {
    name: "Kim",
    age: "22"
  }
};

const obj2 = JSON.parse(JSON.stringify(obj1));
```

<br>
<br>
<br>

## 6. 표(Table)
HTML의 `<table>`태그의 기능으로 대체되어 사용됩니다.

<br>

- **(1)** 헤더 셀을 구분할 때 3개 이상의 -(hyphen/dash) 기호가 필요합니다.
- **(2)** 헤더 셀을 구분하면서 :(colons) 기호로 셀 안에 내용을 정렬 할 수 있습니다.
- **(3)** 가장 좌측과 가장 우측에 있는 | (vertical bar) 기호는 생략 가능합니다.  


```Markdown
**Flex-direction**
|값 | 수평 정렬 | 수직 정렬 | 
|--- | :---: | ---: |           // (1), (2)
| row | 좌측 수평 정렬 | X |
|row-reverse | 우측 수평 정렬 | X |
column | X | 상측 수직 정렬 |    // (3)
column-reverse | X | 하측 수직 정렬 

```
<br>

**위 코드의 실행결과**
<br>
<br>

**Flex-direction**
|값 | 수평 정렬 | 수직 정렬 |
|--- | :---: | ---: |
| row | 좌측 수평 정렬 | X |
|row-reverse | 우측 수평 정렬 | X |
column | X | 상측 수직 정렬 |
column-reverse | X | 하측 수직 정렬 

<br>
<br>
<br>

## 7. 인용문
HTML의 `<blockquote>`태그의 기능으로 대체되어 사용됩니다.

```Markdown
// 화살괄호(Angle brackets)을 사용하여 인용문을 표현합니다. 
> 첫 번째 인용문. 
 
> 두 번쨰 인용문. 

> 세 번째 인용문.
> >네 번째 인용문.
> >>마지막 인용문.
```

<br>

**위 코드의 실행결과**
<br>
<br>
> 첫 번째 인용문. 
 
> 두 번쨰 인용문. 

> 세 번째 인용문.
> >네 번째 인용문.
> >>마지막 인용문.

## 8. 수평선과 줄 바꿈
수평선은 HTML의 `<hr>`태그의 기능으로, 줄바꿈은 HTML의 `<br>`태그의 기능으로 대체되어 사용됩니다. 

- 세 가지 기호("'-','*','_'")중 하나를 3번 연속 입력하여 본문에 수평선을 추가할 수 있습니다. 
- '-'를 사용한 수평선은 수평선 위의 문장을 강조하여 나타내며, 그 외의 수평선들은 모두 같은 기능을 합니다.
- Markdown 문법에서 줄바꿈은, 줄바꿈을 원하는 부분에서 공백(' ')을 두번 입력 후 엔터를 입력해야합니다. 
- 혹은, HTML `<br>`태그를 삽입하여 개행 할 수 있습니다. 

<br>

```Markdown
Lorem ipsum dolor sit amet, consectetur adipiscing elit.
---
Nulla quis eleifend justo. In hac habitasse platea dictumst. 
***
Pellentesque lacinia tortor nec quam consequat, at scelerisque augue sollicitudin.
___

// 줄바꿈을 원하는 부분에서 공백(' ')을 두번 입력 후 엔터를 입력해야, 개행처리가 됩니다. 
Curabitur nisi est, cursus ac ligula id, maximus dapibus lectus. 
Proin tempus pellentesque ipsum, vitae gravida sapien pellentesque non.
Sed tempus, nisi vel consectetur luctus, orci elit pellentesque nisl, id egestas ligula est non quam.
Cras tincidunt est nisi, at sagittis lacus laoreet vel.
Quisque nec urna et ante porttitor cursus ut ut lectus.

```
<br>

**위 코드의 실행결과**
<br>
<br>
Lorem ipsum dolor sit amet, consectetur adipiscing elit.
---
Nulla quis eleifend justo. In hac habitasse platea dictumst. 
***
Pellentesque lacinia tortor nec quam consequat, at scelerisque augue sollicitudin.
___

Curabitur nisi est, cursus ac ligula id, maximus dapibus lectus.   
Proin tempus pellentesque ipsum, vitae gravida sapien pellentesque non.  
Sed tempus, nisi vel consectetur luctus, orci elit pellentesque nisl, id egestas ligula est non quam.  
Cras tincidunt est nisi, at sagittis lacus laoreet vel.  
Quisque nec urna et ante porttitor cursus ut ut lectus.


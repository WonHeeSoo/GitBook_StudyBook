# Markdown Command

현재 추가 중입니다.  
[GitBook Public Study Book](https://wonheesoo.gitbooks.io/study-book/content/markdown/markdown-command.html)

본인이 사용하는 마크다운 도구에 따라 사용이 불가한 방법도 있습니다.

---

## Headings

| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \# 헤더1 | &lt;h1&gt;헤더1&lt;/h1&gt; | 문서의 제목(큰 제목), 글머리 |
| \#\# 헤더2 | &lt;h2&gt;헤더2&lt;/h2&gt; | 문서의 제목(작은 제목), 글머리 |
| \#\#\# 헤더3 | &lt;h3&gt;헤더3&lt;/h3&gt; | 글머리 |
| \#\#\#\# 헤더4 | &lt;h4&gt;헤더4&lt;/h4&gt; | 글머리 |
| \#\#\#\#\# 헤더5 | &lt;h5&gt;헤더5&lt;/h5&gt; | 글머리 |
| \#\#\#\#\#\# 헤더6 | &lt;h6&gt;헤더6&lt;/h6&gt; | 글머리 |

# 헤더1

## 헤더2

### 헤더3

#### 헤더4

##### 헤더5

###### 헤더6

혹은

헤더1

==

헤더2

--

---

## Styling text

| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \*이탤릭체\* | &lt;em&gt;이탤릭체&lt;/em&gt; | 이탤릭체 |
| \_이탤릭체\_ | &lt;em&gt;이탤릭체&lt;/em&gt; | 이탤릭체 |
| \*\*볼드체\*\* | &lt;string&gt;볼드체&lt;/string&gt; | 볼드체 |
| \_\_볼드체\_\_ | &lt;string&gt;볼드체&lt;/string&gt; | 볼드체 |
|\~\~취소선\~\~|&lt;del&gt;취소선&lt;/del&gt;| 취소선 |
| \^윗첨자\^ | &lt;sup&gt;윗첨자&lt;/sup&gt; | 윗첨자 |
| \~아랫첨자\~ | &lt;sub&gt;아랫첨자&lt;/sub&gt; | 아랫첨자 |

_이탤릭체_
**볼드체**
~~취소선~~
윗첨자^윗첨자^
아래첨자~아래첨자~


---

## Quoting code

| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \`인용 코드1\` | &lt;code&gt;인용 코드1&lt;/code&gt; | 인용 코드1 |
| \`\`\`C++(해당언어)          인용 코드2\`\`\` | &lt;pre&gt;인용 코드2&lt;/pre&gt; | 인용 코드2 |

`인용 코드1`

```C++
인용 코드2
```

---

## Quoting text

| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \> 인용구 | | 인용구 |

> 인용구

---

## Links

| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \[링크제목]\(링크주소) | | 링크걸기 |
잘못된 예
[링크제목](링크주소)
올바른 예
[Gitbook StudyBook](https://wonheesoo.gitbooks.io/study-book/content/markdown/markdown-command.html)

---

## Lists

| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \- 리스트1 | | 목차 |
| \* 리스트2 | | 목차 |
| 1\. 리스트3 | | 목차 |

- 리스트1
* 리스트2
1. 리스트3

리스트를 만든 상태에서 바로 아래에 스페이스 두번정도의 공백(  )을 한 뒤 리스트(\-)를 사용하면 기존 리스트의 하위 리스트를 만들수 있다.
- 리스트1
  * 리스트2
    1. 리스트3

---

## Task lists
| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| | | 체크박스 |

---

## Table
```
| 제목1 | 제목2 |
| :-: | :-: |
| 내용1입니다 | 내용2입니다 |
```
| 제목1 | 제목2 |
|  :-:  |  :-:  |
| 내용1입니다 | 내용2입니다 |
---

## Image
| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \!\[제목]\(주소) | | 이미지 출력 |

잘못된 예
![제목](주소)
올바른 예
![ImageExample](https://github.com/WonHeeSoo/GitBook_StudyBook/blob/master/image/Image%20Example.PNG?raw=true)

---

## Video




---

## Using emoji

---

| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \[^1\] |  | 주석 |

---

### 참고
- [GitHub](https://help.github.com/categories/writing-on-github/)
- [Markdown:Syntax](https://daringfireball.net/projects/markdown/syntax)

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

_이탤릭체_

**볼드체**

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

\|제목1\|제목2\|

\|:-:\|:-:\|

\|내용1\|내용2\|

---

| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \^윗첨자\^ | &lt;sup&gt;윗첨자&lt;/sup&gt; | 윗첨자 |
| \~아랫첨자\~ | &lt;sub&gt;아랫첨자&lt;/sub&gt; | 아랫첨자 |
|\~\~취소선\~\~|&lt;del&gt;취소선&lt;/del&gt;| 취소선 |

윗첨자^윗첨자^
아래첨자~아래첨자~
~~취소선~~

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
[링크제목](https://wonheesoo.gitbooks.io/study-book/content/markdown/markdown-command.html)

---

| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \[^1\] |  | 주석 |

---
### 참고
- [GitHub](https://help.github.com/categories/writing-on-github/)
- [Markdown:Syntax](https://daringfireball.net/projects/markdown/syntax)

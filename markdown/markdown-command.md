# Markdown Command

현재 추가 중입니다.  
[GitBook Study Book](https://wonheesoo.gitbooks.io/study-book/content/markdown/markdown-command.html)

본인이 사용하는 마크다운 도구에 따라 사용이 불가한 방법도 있습니다.

---

## Headings

| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \# 헤더1 | &lt;h1&gt;헤더1&lt;/h1&gt; | 문서의 제목(큰 제목), 글머리1(Head1) |
| \#\# 헤더2 | &lt;h2&gt;헤더2&lt;/h2&gt; | 문서의 제목(작은 제목), 글머리2(Head2) |
| \#\#\# 헤더3 | &lt;h3&gt;헤더3&lt;/h3&gt; | 글머리3(Head3) |
| \#\#\#\# 헤더4 | &lt;h4&gt;헤더4&lt;/h4&gt; | 글머리4(Head4) |
| \#\#\#\#\# 헤더5 | &lt;h5&gt;헤더5&lt;/h5&gt; | 글머리5(Head5) |
| \#\#\#\#\#\# 헤더6 | &lt;h6&gt;헤더6&lt;/h6&gt; | 글머리6(Head6) |

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
| \*이탤릭체\* | &lt;em&gt;이탤릭체&lt;/em&gt; | 이탤릭체(Italic) |
| \_이탤릭체\_ | 위와 같음 | 이탤릭체(Italic) |
| \*\*볼드체\*\* | &lt;string&gt;볼드체&lt;/string&gt; | 볼드체(Bold) |
| \_\_볼드체\_\_ | 위와 같음 | 볼드체(Bold) |
|\~\~취소선\~\~|&lt;del&gt;취소선&lt;/del&gt;| 취소선 |
| 위와 같음 |&lt;strike&gt;취소선&lt;/strike&gt;| 취소선 |
| \^윗첨자\^ | &lt;sup&gt;윗첨자&lt;/sup&gt; | 윗첨자 |
| \~아랫첨자\~ | &lt;sub&gt;아랫첨자&lt;/sub&gt; | 아랫첨자 |
||&lt;small&gt;작은 글씨&lt;/small&gt;|작은 글씨|
|\=\=강조\=\=||강조(형광펜느낌)|

_이탤릭체_

**볼드체**

~~취소선~~

윗첨자^윗첨자^

아래첨자~아래첨자~

<small>작은 글씨</small>

==강조==

---

## Quoting code, Fenced code blocks

| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \`Mark인용 코드1\` | &lt;code&gt;Tag인용 코드1&lt;/code&gt; | 인용 코드1 |
| \`\`\`C++(해당언어)          Mark인용 코드2\`\`\` | &lt;pre&gt;Tag인용 코드2&lt;/pre&gt; | 인용 코드2 |
| 위와 같음 | &lt;pre&gt;&lt;code&gt;Tag인용 코드3&lt;/code&gt;&lt;/pre&gt; | 인용 코드3 |

`Mark인용 코드1`

<code>Tag인용 코드1</code>

```C++
Mark인용 코드2
```
<pre>Tag인용 코드2</pre>

<pre><code>Tag인용 코드3</code></pre>

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
| \[링크제목]\(링크주소) | &lt;a href\=\"링크주소\"&gt;링크제목&lt;\/a&gt; | 링크걸기(Link) |
| 링크주소 | | 링크걸기(Link automatic) |

<a href="https://wonheesoo.gitbooks.io/study-book/content/markdown/markdown-command.html">링크걸기</a>

#### 잘못된 예

[링크제목](링크주소)

#### 올바른 예

[Gitbook StudyBook](https://wonheesoo.gitbooks.io/study-book/content/markdown/markdown-command.html)

https://wonheesoo.gitbooks.io/study-book/content/markdown/markdown-command.html

---

## Lists

| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \- 리스트1 | &lt;ul&gt;&lt;li&gt;리스트1&lt;/li&gt;&lt;/ul&gt; | 목록(unordered list) |
| \* 리스트2 | 위와 같음 | 목록(unordered list) |
| \+ 리스트3 | 위와 같음 | 목록(unordered list) |
| 1\. 리스트4 | &lt;ol&gt;&lt;li&gt;리스트4&lt;/li&gt;&lt;/ol&gt; | 목록(ordered list) |

#### Markdown Command Only

- 리스트1
* 리스트2
+ 리스트3
1. 리스트4

#### HTML Tag Only
```
<ol>
  <li>리스트4-1</li>
  <li>리스트4-2</li>
</ol>
```

<ol>
	<li>리스트4-1</li>
  <li>리스트4-2</li>
</ol>

```
<ul>
  <li>리스트1-1</li>
  <li>리스트1-1</li>
  <li>리스트1-1</li>
    <ol>
      <li>리스트4-3</li>
      <li>리스트4-4</li>
    </ol>
</ul>
```

<ul>
	<li>리스트1-1</li>
	<li>리스트1-1</li>
	<li>리스트1-1</li>
	  <ol>
		  <li>리스트4-3</li>
		  <li>리스트4-4</li>
		</ol>
</ul>


#### 그 이외

리스트를 만든 상태에서 바로 아래에 스페이스 두번정도의 공백(  )을 한 뒤 리스트(\-)를 사용하면 기존 리스트의 하위 리스트를 만들수 있다.

```
- 리스트1
  * 리스트2
    1. 리스트3
```

- 리스트1
  * 리스트2
    1. 리스트3

---

## Task lists

| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \- \[ ] | | 체크박스\(false\) |
| \- \[x] | | 체크박스\(true\) |

- [ ] 체크박스\(false\)

- [x] 체크박스\(true\)

[GitHub Task Lists](https://help.github.com/articles/about-task-lists/)

---

## Table

#### Markdown Command만 사용한 예

```
| 제목1 | 제목2 | 제목3 | 제목4 |
| :- | - | :-: | -: |
| 내용1입니다 | 내용2입니다 | 내용3입니다 | 내용4입니다 |
| 내용1 | 내용2 | 내용3 | 내용4 |
```

| 제목1 | 제목2 | 제목3 | 제목4 |
| :- | - | :-: | -: |
| 내용1입니다 | 내용2입니다 | 내용3입니다 | 내용4입니다 |
| 내용1 | 내용2 | 내용3 | 내용4 |

#### HTML Tag를 포함해 사용한 예

```
| <center>제목1</center> | 제목2 | 제목3 | <center>제목1</center> |
| :- | - | :-: | -: |
| 내용1입니다 | 내용2입니다 | 내용3입니다 | 내용4입니다 |
| 내용1 | 내용2 | 내용3 | 내용4 |
```

| <center>제목1</center> | 제목2 | 제목3 | <center>제목1</center> |
| :- | - | :-: | -: |
| 내용1입니다 | 내용2입니다 | 내용3입니다 | 내용4입니다 |
| 내용1 | 내용2 | 내용3 | 내용4 |

#### 그 이외

- ##### 표를 사용할때 `-`의 수는 상관없다.

```
| 제목1 | 제목2 | 제목3 | 제목4 |
| :---- | ------ | :----------: | --------------------: |
| 내용1입니다 | 내용2입니다 | 내용3입니다 | 내용4입니다 |
| 내용1 | 내용2 | 내용3 | 내용4 |
```

| 제목1 | 제목2 | 제목3 | 제목4 |
| :---- | ------ | :----------: | --------------------: |
| 내용1입니다 | 내용2입니다 | 내용3입니다 | 내용4입니다 |
| 내용1 | 내용2 | 내용3 | 내용4 |

- ##### 특정 방향으로 정렬해도 HTML Tag인 `<center></center>`를 사용하면 가운데 정렬된다.

```
| <center>제목1</center> |  <center>제목2</center> |
| :- |  -: |
| <center>내용1입니다</center> | <center>내용2입니다</center> |
| 내용1 | 내용2|
| <center>내용1</center> | <center>내용2</center> |
```

| <center>제목1</center> |  <center>제목2</center> |
| :- |  -: |
| <center>내용1입니다</center> | <center>내용2입니다</center> |
| 내용1 | 내용2|
| <center>내용1</center> | <center>내용2</center> |

---

## Image
| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \!\[제목]\(주소, 확장자명) | &lt;img alt\=\"제목\" src\=\"주소, 확장자명\" \/&gt; | 이미지 출력 |

#### 잘못된 예

![제목](주소)

#### 올바른 예\(Markdown Syntax\)

```
![ImageExample](https://github.com/WonHeeSoo/GitBook_StudyBook/blob/master/image/Image%20Example.PNG?raw=true)
```

![ImageExample](https://github.com/WonHeeSoo/GitBook_StudyBook/blob/master/image/Image%20Example.PNG?raw=true)

#### 올바른 예\(HTML Tag\)

```
<img alt="ImageExample" src="https://github.com/WonHeeSoo/GitBook_StudyBook/blob/master/image/Image%20Example.PNG?raw=true" />
```

<img alt="ImageExample" src="https://github.com/WonHeeSoo/GitBook_StudyBook/blob/master/image/Image%20Example.PNG?raw=true" />

---

## Video

---

## Horizontal Rules

| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \-\-\- | &lt;hr/&gt; | 수평선 |
| \*\*\* | 위와 같음 | 수평선 |
| \_\_\_ | 위와 같음 | 수평선 |

---

***

___

<hr/>

---

## Backslash escapes

| Markdown Syntax | Description |
| :--- | :--- |
| \\\\ | backslash |
| \\\` | backtick |
| \\\* | asterisk |
| \\\_ | underscore |
| \\\{ | curly braces |
| \\\} | curly braces |
| \\\[ | square brackets |
| \\\] | square brackets |
| \\\( | parentheses |
| \\\) | parentheses |
| \\\# | hash mark |
| \\\+ | plus sign |
| \\\- | minus sign (hyphen) |
| \\\. | dot |
| \\\! | exclamation mark |

\\

\`

\*

\_

\{ \}

\[ \]

\( \)

\#

\+

\-

\.

\!

---

## Username @mentions \( GitHub Flavored Markdown \)

`@유저닉네임`을 사용하면 그 유저닉네임을 가진 사람에게 댓글을 보도록 알릴 수 있습니다.

혹은 조직 내의 팀에게도 사용 가능합니다.

#### 원문
> Typing an @ symbol, followed by a username, will
notify that person to come and view the comment\.
This is called an “@mention”, because you’re
mentioning the individual\. You can also @mention
teams within an organization\.


---

## Using emoji \( GitHub Flavored Markdown \)

| Markdown Syntax | Description |
| :--- | :--- |
| `:+1:` | +1 |
| `:sparkles:` | sparkles |
| `:camel:` | camel |
| `:tada:` | tada |
| `:rocket:` | rocket |
| `:metal:` | metal |
| `:octocat:` | octocat |

:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat:

#### 추가적인 Emoji

[EMOJI CHEAT SHEET](https://www.webpagefx.com/tools/emoji-cheat-sheet/)

---

| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \[^1\] |  | 각주 |

---

Footnotes
git 과정 하위로 git command 만들기

### 참고
- [GitHub](https://help.github.com/categories/writing-on-github/)
- [Github-cheatsheet](https://enterprise.github.com/downloads/en/markdown-cheatsheet.pdf)
-  [Markdown:Syntax](https://daringfireball.net/projects/markdown/syntax)
- [Wikipedia-Markdown](https://en.wikipedia.org/wiki/Markdown)

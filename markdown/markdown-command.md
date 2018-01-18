# Markdown Syntax

현재 추가 중입니다.  
## [GitBook Study Book](https://wonheesoo.gitbooks.io/study-book/content/markdown/markdown-command.html)

본인이 사용하는 마크다운 도구에 따라 사용이 불가한 방법도 있습니다.

Markdown Syntax를 정리하면서 참고한 곳들은 다음과 같습니다.

- [GitHub](https://help.github.com/categories/writing-on-github/)
- [Github-cheatsheet](https://enterprise.github.com/downloads/en/markdown-cheatsheet.pdf)
-  [Markdown:Syntax](https://daringfireball.net/projects/markdown/syntax)
- [Wikipedia-Markdown](https://en.wikipedia.org/wiki/Markdown)
- [markdown-here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#youtube-videos)
- [유튜브의 동영상 썸네일 가져오기](http://superkts.pe.kr/helper/view.php?seq=V&seq=377)
- [StackOverflow: Is it possible to embed Youtube/Vimeo videos in Markdown using a C# Markdown library
](https://stackoverflow.com/questions/14192709/is-it-possible-to-embed-youtube-vimeo-videos-in-markdown-using-a-c-sharp-markdow/29862668#29862668)




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

#### 그 이외

```
헤더1
==
```

헤더1
==

```
헤더2
--
```

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
||&lt;u&gt;밑줄&lt;/u&gt;|밑줄|
|\~\~취소선\~\~|&lt;del&gt;취소선&lt;/del&gt;| 취소선 |
| 위와 같음 |&lt;strike&gt;취소선&lt;/strike&gt;| 취소선 |
| ^윗첨자^ | &lt;sup&gt;윗첨자&lt;/sup&gt; | 윗첨자 |
| \~아랫첨자\~ | &lt;sub&gt;아랫첨자&lt;/sub&gt; | 아랫첨자 |
||&lt;small&gt;작은 글씨&lt;/small&gt;|작은 글씨|
|==강조==||강조(형광펜느낌)|

_이탤릭체_

**볼드체**

<u>밑줄</u>

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

리스트를 만든 상태에서 바로 아래에 스페이스 두번정도의 공백(  )을 한 뒤 리스트(\-)를 사용하면 기존 리스트의 하위 리스트를 만들수 있습니다.

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

- ##### 표를 사용할때 `-`의 수는 상관없습니다.

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

- ##### 특정 방향으로 정렬해도 HTML Tag인 `<center></center>`를 사용하면 가운데 정렬이 됩니다.

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

## Horizontal Rules

| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \-\-\- | &lt;hr/&gt; | 수평선 |
| \*\*\* | 위와 같음 | 수평선 |
| \_\_\_ | 위와 같음 | 수평선 |

### `---` 사용했을 때

---

### `***` 사용했을 때

***

### `___` 사용했을 때

___

### `<hr/>` 사용했을 때

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

## Footnotes

| Markdown Syntax | HTML Tag | Description |
| :--- | :--- | :--- |
| \[^1\] |  | 각주 |

```
Hexo[^1]는 Hexo입니다.
[^1]:Hexo는 블로그 프레임워크입니다.
```

Hexo[^1]는 Hexo입니다.

[^1]:Hexo는 블로그 프레임워크입니다.

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

Markdwon은 기본적으로 동영상을 지원하지 않으나 도구에 따라 마크다운 문법이 확장되어 단순히 주소만 복사해줘도 동영상을 올리는 것이 가능하지 않을 때 사용합니다.

최소한의 코드는 다음과 같습니다.
`[![영상 제목](이미지주소)](영상주소)`

일종의 트릭으로 Markdwon의 Link(`[링크제목](링크주소)`)와 Image(`![제목](주소)`)를 사용하여 Image자체를 링크의 제목으로 만들고 링크주소를 걸어주면 됩니다.

## Youtube

### Youtube Thumbnail을 사용하는 방법

[![BTS DNA Youtube](https://img.youtube.com/vi/MBdVXkSdhwU/0.jpg)](https://www.youtube.com/watch?v=MBdVXkSdhwU)
`
[![BTS DNA Youtube](https://img.youtube.com/vi/MBdVXkSdhwU/0.jpg)](https://www.youtube.com/watch?v=MBdVXkSdhwU)
`

위의 코드 중에서 이미지 주소인 `https://img.youtube.com/vi/MBdVXkSdhwU/0.jpg)`, 특히 끝부분을 보면 `MBdVXkSdhwU/0`라는 부분이 있는데 영상의 링크 주소를 확인해보면 `MBdVXkSdhwU`이 존재함을 알 수 있고 동영상의 고유 주소임을 알 수 있습니다.

여기서 추가적으로 `/0`부분이 의미하는 것은 고유의 코드로 영상 게시자가 선택한 Thumbnail을 우리가 사용할 수 있습니다.

또한 `/0` 대신 `/1`, `/2`, `/3`, `/default`, `/mqdefault`, `/hqdefault`, `/dsdefault`, `/maxresdefault`을 사용할 수 있습니다.

#### `/1`을 사용한 예

[![BTS DNA Youtube/1](https://img.youtube.com/vi/MBdVXkSdhwU/1.jpg)](https://www.youtube.com/watch?v=MBdVXkSdhwU)

#### `/2`을 사용한 예

[![BTS DNA Youtube/2](https://img.youtube.com/vi/MBdVXkSdhwU/2.jpg)](https://www.youtube.com/watch?v=MBdVXkSdhwU)

#### `/3`을 사용한 예

[![BTS DNA Youtube/3](https://img.youtube.com/vi/MBdVXkSdhwU/3.jpg)](https://www.youtube.com/watch?v=MBdVXkSdhwU)

#### `/default`을 사용한 예

[![BTS DNA Youtube/default](https://img.youtube.com/vi/MBdVXkSdhwU/default.jpg)](https://www.youtube.com/watch?v=MBdVXkSdhwU)

#### `/mqdefault`을 사용한 예

[![BTS DNA Youtube/mqdefault](https://img.youtube.com/vi/MBdVXkSdhwU/mqdefault.jpg)](https://www.youtube.com/watch?v=MBdVXkSdhwU)

#### `/hqdefault`을 사용한 예

[![BTS DNA Youtube/hqdefault](https://img.youtube.com/vi/MBdVXkSdhwU/hqdefault.jpg)](https://www.youtube.com/watch?v=MBdVXkSdhwU)

#### `/sddefault`을 사용한 예

[![BTS DNA Youtube/sddefault](https://img.youtube.com/vi/MBdVXkSdhwU/sddefault.jpg)](https://www.youtube.com/watch?v=MBdVXkSdhwU)

#### `/maxresdefault`을 사용한 예

[![BTS DNA Youtube/sddefault](https://img.youtube.com/vi/MBdVXkSdhwU/maxresdefault.jpg)](https://www.youtube.com/watch?v=MBdVXkSdhwU)

### Youtube Video Thumbnail을 사용하는 방법

[![Everything Is AWESOME](https://i.ytimg.com/an_webp/MBdVXkSdhwU/mqdefault_6s.webp?du=3000&sqp=CJmTg9MF&rs=AOn4CLDAp7iix1IMI4mn2VTQzd5SBz9lmA)](https://www.youtube.com/watch?v=MBdVXkSdhwU)
`[![Everything Is AWESOME](https://i.ytimg.com/an_webp/MBdVXkSdhwU/mqdefault_6s.webp?du=3000&sqp=CJmTg9MF&rs=AOn4CLDAp7iix1IMI4mn2VTQzd5SBz9lmA)](https://www.youtube.com/watch?v=MBdVXkSdhwU)`

원하는 영상을 검색한뒤 Youtube Video Thumbnail이 작동하는 영상을 마우스 우클릭을 해 이미지 주소 복사를 합니다.

### Youtube 특정 시간대 영상 재생하기

[![Everything Is AWESOME](https://img.youtube.com/vi/MBdVXkSdhwU/0.jpg)](https://youtu.be/MBdVXkSdhwU?t=29)
`[![Everything Is AWESOME](https://img.youtube.com/vi/MBdVXkSdhwU/0.jpg)](https://youtu.be/MBdVXkSdhwU?t=29)`

Thumbnail의 크기나 이미지를 선택하기 위해 각 영상들만의 고유코드 뒤에 `/0`이나 `/default`같은 것을 붙였고 시간의 경우 고유코드 뒤에 `/?t=원하는시간`을 적으면 특정 시간대에서 부터 영상을 재생시킬 수 있으며 `?t=10`은 영상의 10초 구간이며 default 값은 초(Seconds)로 계산합니다.

예를 들어 단순히 숫자 10를 적으면 영상의 10초(Seconds)에 해당하는 구간으로 이동하지만 `/?t=10m`이면 영상의 10분에 해당하는 구간, `/?t=10h`이면 영상의 10시간에 해당하는 구간부터 영상을 재생시킬 수 있습니다.

`/?t=1m24s`같이 시,분,초를 섞을 수 있습니다.

만약 영상의 길이보다 긴 시간을 적는 다면 영상의 끝 부분으로 이동해 영상이 끝나거나 다시 영상의 첫 부분부터 다시 재생이 됩니다.

### HTML Tag을 사용하는 방법

#### HTML Tag를 사용하기

<div align="center"> <a href="https://www.youtube.com/watch?v=MBdVXkSdhwU
" target="_blank"><img src="https://img.youtube.com/vi/MBdVXkSdhwU/0.jpg"
alt="BTS DNA Youtube" width="500" height="360" border="4" /></a></div>
```
<div align="center">
  <a href="https://www.youtube.com/watch?v=MBdVXkSdhwU
" target="_blank"><img src="https://img.youtube.com/vi/MBdVXkSdhwU/0.jpg"
alt="BTS DNA Youtube" width="500" height="360" border="4" /></a>
</div>
```

#### 최소한의 HTML Tag만 사용하기

<a href="https://www.youtube.com/watch?v=MBdVXkSdhwU">
<img src="https://img.youtube.com/vi/MBdVXkSdhwU/0.jpg" ></a>
```
<a href="https://www.youtube.com/watch?v=MBdVXkSdhwU">
<img src="https://img.youtube.com/vi/MBdVXkSdhwU/0.jpg" ></a>
```


#### 최소한의 HTML Tag만 사용하기 + 제목

<a href="https://www.youtube.com/watch?v=MBdVXkSdhwU">
<img src="https://img.youtube.com/vi/MBdVXkSdhwU/0.jpg"
alt="BTS DNA Youtube"></a>
```
<a href="https://www.youtube.com/watch?v=MBdVXkSdhwU">
<img src="https://img.youtube.com/vi/MBdVXkSdhwU/0.jpg"
alt="BTS DNA Youtube"></a>
```

## vimeo

### Vimeo Thumbnail을 사용하는 방법

[![Young Marco](https://i.vimeocdn.com/video/625196300_560x290.jpg)](https://vimeo.com/209607366)
`[![Young Marco](https://i.vimeocdn.com/video/625196300_560x290.jpg)](https://vimeo.com/209607366)`

동영상 이미지의 경우 오른쪽 하단에 위치한 다음 동영상 자동 재생에서 이미지 주소 복사를 하거나 따로 이미지를 구해서 주소 복사를 합니다.

Vimeo의 경우 이미지 주소 뒤에 `_가로x세로.jpg`를 붙이면 원하는 크기로 출력됩니다.

### Vimeo 특정 시간대 영상 재생하기

[![Young Marco](https://i.vimeocdn.com/video/625196300_560x290.jpg)](https://vimeo.com/209607366#t=3s)
`[![Young Marco](https://i.vimeocdn.com/video/625196300_560x290.jpg)](https://vimeo.com/209607366#t=3s)`

Vimeo는 영상 주소 뒤에 `#t=시간`을 붙이면 됩니다. Youtube와 마찬가지로 default값은 초(Seconds)이며 `m`, `h`를 사용할 수 있으며 Youtube처럼 `#t=1m20s` 이런 식으로 섞을 수 있습니다.

만약 영상의 길이보다 긴 시간을 적는 다면 영상의 끝 부분으로 이동해 영상이 끝납니다.

### 다른 동영상 플레이어의 경우

그에 맞는 API를 사용하거나 없다면 단순히 링크 주소만 사용합니다.

## Regular Expression
### References
* 깃허브 정리⇢ [https://github.com/dream-ellie/regex](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbjk4Q3lIYUZGSjZ5V0Jtc3dsbGFETFVhMWtPUXxBQ3Jtc0tsRVp1bnVNOXRwRExiVEtDQXNCc2x5MEkycG5PUWZYUWJsVVNZRFVqZThmMjhQdzZmenRUeGpCR1VDXzZvUFZNSlE5T0U1YUlWWWlKLUtibF9HcDBtOWh3MFkyX3IwRTMtSExkLU44YXJJZlhaTFJ3bw&q=https%3A%2F%2Fgithub.com%2Fdream-ellie%2Fregex)
* 연습용 사이트(강의노트) ⇢ regexr.com/5mhou
* RegexOne(퀴즈) ⇢ [https://regexone.com/](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbmZKb0dFcmoxMmxtTDQ2SXEzTUstdm1sTXQwQXxBQ3Jtc0trUjFZMDN3VkJGcGVlRjFwM2gzMnBvMXBDdGZJUGhJalRWODBVUVM3ZlltVWNudGdiblAxX3VBUU5BTFhZbWM3a0JCcFZneW5pc2J2enNYMG1wdjJ2UWlSSVJTZ0c4RUdiY2NxYVBYbWFEUjVhb3lpNA&q=https%3A%2F%2Fregexone.com%2F)

## 다양한 표현식
### Groups and ranges
|charater|contents|
|------|---|
| ```\|``` |또는|
|```()```|그룹|
|```[]```|문자셋, 괄호안의 어떤 문자든|
|```[^]```|부정 문자셋, 괄호 안에 어떤 문자가 아닐 때|
|```(?:)```|찾지만 기억하지는 않음|

### Quantifiers
|character|contents|
|----|----|
|```?```|있거나 없거나 (zero or one)|
|```*```|없거나 있거나 많거나 (zero or more)|
|```+```|하나 또는 많이 (one or more)|
|```{n}```|n번 반복|
|```{min,}```|최소|
|```{min,max}```|최소, 그리고 최대|

### Boundary-type
|character|contents|
|----|----|
|```\b```|단어 경계|
|```\B```|단어 경계가 아님|
|```\^```|문장의 시작|
|```\$```|문장의 끝|

### Character classes
|character|contents|
|----|----|
|```\ ```|특수문자가 아닌 문자|
|```.```|어떤 글자 (줄바꿈 문자 제외)|
|```\d```|digit 숫자|
|```\D```|digit 숫자가 아님|
|```\w```|word 문자|
|```\W```|word 문자가 아님|
|```\s```|space 공백|
|```\S```|space 공백이 아님|
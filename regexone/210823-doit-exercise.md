## 파이썬생활프로그래밍 연습문제
### Exercise 1) Regex - 반복문으로 연습하기
```python
words = ['apple', 'cat', 'brave', 'drama', 'arise', 'blow', 'coat', 'above']
for i in words:
    m = re.match(r'a\D+', i)
    if m:
        print(m.group())
```


### Exercise 2) Regex - 메일주소 추출
```python
a = '제 이메일 주소는 greatking@naver.com입니다. 오늘 저는 travel@daum.net 라는 주소로 메일을 보내려고 합니다. 저는 apple@gmail.com, life@abc.co.kr 라는 메일도 사용하고 있습니다.'
b = re.findall(r'[a-z]+@[A-Za-z0-9.]+', a)
```


### Exercise 3) Regex - 마침표(.) 활성화 시키기
```python
exam = '저는 92년에 태어났습니다. 88년에는 올림픽이 있었습니다. 지금은 2020년입니다.'
re.findall(r'\d.+?년', exam)
```

### Exercise 4) Regex - 문장별으로 끊어 리스트화 하기
```python
d = 'I have a dog. I am not a girl. You are not alone. I am happy.'
re.split(r'[.?]',d)
```



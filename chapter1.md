---
title: '2주차 과제_90일'
description: 'Chapter description goes here.'
---

## 컨벤션에 대해서

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```

(각 2점)

식별자 이름의 형태를 통해 직관적으로 이것이 함수인지, 변수인지 혹은 클래스명을 바로 알 수 있습니다.

저희가 아직 실질적으로 함수, 클래스를 만드는 방법을 배우지는 않았지만, 미리 컨벤션 규칙을 익히려 합니다.

`@instructions`
아래 단어를 활용하여 변수명, 함수명, 클래스명을 컨벤션 규칙에 따라 작성해주세요.

**_customer list_**

`@hint`
띄워쓰기 불가 / 숫자로 시작 불가 / 한글 불가 / 이미 선언된 함수명은 피하세요

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# customer list

# (1) 아래에 NAME 를 지우고 위 단어로 컨벤션에 맞게 함수명을 작성해주세요.

def NAME():
  pass

# (2) 아래에 %%%% 를 지우고 위 단어로 컨벤션에 맞게 변수명을 입력해주세요.

NAME = 900

# (3) 아래에 %%%% 를 지우고 위 단어로 컨벤션에 맞게 클래스명을 입력해주세요.
# class 아래에 def, self 등 코드는 지금은 신경쓰지 않으셔도 됩니다.

class NAME(object):
  def __init__(self):
    self.name = "Hello"
```

`@solution`
```{python}
# (1) 아래에 NAME 를 지우고 위 단어로 컨벤션에 맞게 함수명을 작성해주세요.

def customer_list():
  pass

# (2) 아래에 NAME 를 지우고 위 단어로 컨벤션에 맞게 변수명을 입력해주세요.

customer_list = 900

# (3) 아래에 NAME 를 지우고 위 단어로 컨벤션에 맞게 클래스명을 입력해주세요.
# class 아래에 def, self 등 코드는 지금은 신경쓰지 않으셔도 됩니다.

class customerList(object):
  def __init__(self):
    self.name = "Hello"
```

`@sct`
```{python}

```

---

## 주피터 노트북 (Colab) 에서 Shell command (bash) 사용하기

```yaml
type: NormalExercise
key: c9d9e18436
lang: python
xp: 100
skills: 2
```

(3 점)

분석 업무를 본인 PC 에서 작업을 한다면, 파일을 찾거나 저장, 이동을 윈도우 탐색기(macOS 는 Finder) 로 편리하게 작업이 가능합니다.

그러나 마우스를 활용할 수 없는 환경에서는 Shell command 를 통해 원하는 파일을 가져오거나, 저장, 삭제, 이동 등을 할 수 있습니다.

여기에서는 주피터 노트북에서 Shell command 를 사용하는 방법을 간단히 알아보겠습니다.

`@instructions`
Shell command 를 사용하여 파일 목록을 출력해주는 코드를 작성해보세요.

`@hint`
목록은 영어로 list입니다.

`@pre_exercise_code`
```{python}
!touch 설명서.txt
```

`@sample_code`
```{python}
# Shell command 를 사용하여 파일 목록을 출력해주는 코드를 작성해보세요.

```

`@solution`
```{python}
# Shell command 를 사용하여 파일 목록을 출력해주는 코드를 작성해보세요.
!ls
```

`@sct`
```{python}

```

---

## 숫자(int, float) 와 문자(str) 를 합치는 방법

```yaml
type: NormalExercise
key: 3dfa85607f
lang: python
xp: 100
skills: 2
```

(5 점)

아래 a + b 를 실행 했을 때 1문자 로 합칠 수 있게 해주세요.

`@instructions`
아래 a + b 를 실행 했을 때 **1문자** 로 합칠 수 있게 해주세요.
a = 1
b = "문자"

`@hint`
숫자와 문자는 더 할 수 없습니다.

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
a = 1
b = "문자"

# "1문자" 가 출력되도록 코드를 작성해주세요.
```

`@solution`
```{python}
a = 1
b = "문자"

# "1문자" 가 출력되도록 코드를 작성해주세요.

str(a) + b
```

`@sct`
```{python}

```

---

## 전화번호에서 지역번호만 가져오기

```yaml
type: NormalExercise
key: ad79063701
lang: python
xp: 100
skills: 2
```

(5 점)

아래 tel 이라는 변수에 전화번호가 저장되어 있습니다. 여기에서 인덱스 값을 활용하여 지역번호만 code 라는 변수에 저장하는 코드를 작성해주세요.

`@instructions`
tel = "031-1111-2222"

`@hint`
:를 이용하여 스트링을 슬라이싱 할 수 있습니다.

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# 아래 코드를 완성해주세요.
# 코드 일부분을 입력해놓았습니다. 활용하셔도 되고 혹은 지우고 원하는 방법으로 만들어보세요.
tel = "031-1111-2222"
code = tel[]



# 결과를 확인해보는 코드입니다. 
print(code)
```

`@solution`
```{python}
# 아래 코드를 완성해주세요.
# 코드 일부분을 입력해놓았습니다. 활용하셔도 되고 혹은 지우고 원하는 방법으로 만들어보세요.
tel = "031-1111-2222"
code = tel[:3]



# 결과를 확인해보는 코드입니다. 
print(code)
```

`@sct`
```{python}

```

---

## 반대로 순서를 뒤집기

```yaml
type: NormalExercise
key: c9dc8fd90d
lang: python
xp: 100
skills: 2
```

(5 점)

order 라는 변수에 1,2,3,4,5,6,7,8,9 문자열이 저장되어 있습니다. 이를 거꾸로 출력하는 코드를 작성해주세요.

**_반드시 인덱스 기능을 활용해야 합니다._**

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
order = "1,2,3,4,5,6,7,8,9"

# 아래에 코드를 완성해주세요.
# 코드 일부분을 입력해놓았습니다. 활용하셔도 되고 혹은 지우고 원하는 방법으로 만들어보세요.
order[]


# 결과를 확인해보는 코드입니다.
print(order)
```

`@solution`
```{python}
order = "1,2,3,4,5,6,7,8,9"

# 아래에 코드를 완성해주세요.
# 코드 일부분을 입력해놓았습니다. 활용하셔도 되고 혹은 지우고 원하는 방법으로 만들어보세요.
order[::-1]


# 결과를 확인해보는 코드입니다.
print(order)
```

`@sct`
```{python}

```

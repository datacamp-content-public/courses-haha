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
#SUBMISSION CORRECTNESS TESTS
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
#SUBMISSION CORRECTNESS TESTS
```

# 실수모음

## 사용하기 전에 생각했나요?

### ▶ GIT

`git init`

> 1. GIT BASH에서 master상태가 아닌가요?
>   
> 2. 상위/하위 디렉토리가 master상태인가요?
>   

`git clone GIT_ADDRESS`

> 1. 해당 주소에 접근하기 위한 자격이 있나요?
>   
>   > 자격 증명 관리자 - Windows 자격 증명 - 일반 자격 증명
>   
> 2. 이전에 이미 clone을 했나요?
>   

`git remote add origin GIT_ADDRESS`

> 1. GIT BASH에서 master상태가 아닌가요?
>   
> 2. 상위/하위 디렉토리가 master상태인가요?
>   
> 3. GIT_ADDRESS가 정확한 주소인가요?
>   
> 4. `git init`을 했나요?
>   

`git push origin master`

> 1. 푸쉬 할 깃 허브/랩과 상태가 동일한가요?
>   
> 2. 동일하지 않다면 `git pull origin master`을 했나요?
>   
> 3. 커밋할 파일을 저장했나요?
>   
> 4. `git add`와 `git commit`을 했나요?`
>   
> 5. `git log`에 방금 추가한 커밋이 존재하나요?
>   

`git pull origin master`

> 1. 푸쉬할 깃 허브/랩과 상태가 동일한데도 하고있나요?
>   
> 2. 혹시 `git clone`을 사용하려던 것이 아니었나요?
>   

### ▶ PYTHON

`print('hi, %s' % name)`

> %-formattiong
>

`print('hi, {}'.format(name)`

> str.format()
>

`print(f'hi, {name}')

> f-string
>

`a is b, a == b`

> is 는 id까지 같음을 의미함
>
> == 는 값이 같음을 의미함
>

`imlist[-1]`

> 뒤에서 첫 번째 값에 접근

`num if num >= 0 else - num`

> abs(num)
>
> Conditional Experssion
>

`a = dict(b=80, c=40)`
`for i in a:`

> i는 b와 c임
>
> i를 통해 80과 40에 접근 가능
>

`[i for i in range(10) if condition]`

> List Comprehension
>
> 0부터 9까지 condition을 충족한 리스트
>

`{i: i*2 for i in range(10) if condition}`

> Dictionary Comprehension
>
> 키값은 0부터 9까지, 키의 2배수가 값으로 condition을 충족한 딕셔너리
>

`break`

> 반복 중단
>

`continue`

> 이번 반복만 넘어감
>

`pass`

> 파업
>

`for-else`

> for 다 돌고 else 실행
>
> break로 종료하면 else는 안 함
>

`def func(*args):`

> 여러 인자를 한 번에 받기
>
> tuple로 취급하여 받아옴
>

`def func(**kwargs):`

> 여러 인자를 key=value형태로 받기
>
> dictionary로 취급하여 받아옴
>

LEGB

> Local, Enclosed, Global, Built-in
>

`lambda a, b: a * b`

> 이름 없는 함수
>
> lambda 인자: return값 구조
>


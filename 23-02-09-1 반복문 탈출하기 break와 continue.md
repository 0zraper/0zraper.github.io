```python
for i in range(10):
    if i > 5 :
        break   # break 만나면 반복문을 빠져 나간다.
    print(i)
```

    0
    1
    2
    3
    4
    5



```python
 for i in range(10):
    print(i)         # 프린트를 먼저하니 6까지 프린트 후 아래로 가서 조건문의 참이 되어 아래 브레이크 실행 한다.
    if i > 5 :
        break   # 
    
```

    0
    1
    2
    3
    4
    5
    6



```python
for i in range(10):
    print("현재i는",i,"break")   # 현재아이는 출력+ 6 + 브레이크 를 출력함
    if i > 5 :
        break
# 반복문의 끝
```

    현재i는 0 break
    현재i는 1 break
    현재i는 2 break
    현재i는 3 break
    현재i는 4 break
    현재i는 5 break
    현재i는 6 break



```python
for i in range(10):
    if i > 5 :
            print("현재i는",i,"break")   # 현재아이는 출력+ 6 + 브레이크 를 출력함

            break
# for 반복문의 끝
print("for문은 끝났어요")
```

    현재i는 6 break
    for문은 끝났어요



```python
for i in range(10):
    print(i)
    break           # 조건문 없이 브레이크면 하나 출력 후 브레이크후 반복문루프에서 나온다
print("반목문은 끝남")
```

    0
    반목문은 끝남



```python
# 반복문 특정 조건만 건너띄기 ( continue)

## 반복문에서 continue 를 만나면 들여쓰기 된 코드는 실행하지 않고 다음 반복으로 이동.
## 예) 홀수만 출력하기 - 현재 숫자가 짝수이면 다음 반복으로 이동.

```


```python
for i in range(10):  # 조건문이 참이면 컨티뉴를 만나러 가는것이다. 폴스면 컨티뉴 못만나고 건너띄어 프린트로 간다.
    if i % 2 == 0:  # % 연산자는 나머지 연산자이다 나머지가 몇인가 물어보는것임 0%2= 나머지0 참임-출력안함 돌아가, 1%2=못나눔(나머지 1 거짓-출력) 2%2=1(나머지0참-다시)
        continue    #조건식이 참이면 컨티뉴를 만나 아래 실행하지 않고 처음  반복문으로 돌아감
    print(i)        # 조건식에서 폴스면 컨티뉴를 건너띄고 아래로 와서 프린트를 실행한다.
```

    1
    3
    5
    7
    9



```python
0%2  ### 2로 나누기 하고 나머지는 홀수 일때만 나머지가 0이다
```




    0




```python
1%2  ### i % 2 == 0 조건은 짝수를 판별하는 조건식이다.
```




    1




```python
2%2  ### i % 2 == 1 조건은 홀수를 판별하는 조건식이다.
```




    0




```python
3%2
```




    1




```python

```

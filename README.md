# PythonStudy
Python Study Note

### 变量
- 除法
```
>>> 9 / 3
3.0
>>> 10 // 3
3
```

- 字符串多个空行
```
print('''line1
line2
line3''')
```

### list,tuple
- **list**:可变数组`classmates = ['Michael', 'Bob', 'Tracy']`
 ```
 classmates[-1] #末尾元素
 classmates.pop() #删除末尾元素
 classmates.pop(1) #删除索引1元素
 classmates[1] = "Chen"  ##替代元素
 classmates.insert(1,'Jack')
 classmates.append('Bai')
 ```
- **tuple**:不可变数组`classmates = ('Michael', 'Bob', 'Tracy')`
  `t = (1,)` #只有一个元素时须加，

### 条件判断  
```
age = 3
if age >= 18:
    print('your age is', age)
    print('adult')
else:
    print('your age is', age)
    print('teenager')
```
":"代表后面缩紧的部分都是他的块。

### 循环
- for x in ...: 遍历
```
sum = 0
for x in [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]:
    sum = sum + x
print(sum)
```

- random()函数:
```
>>> range(5)
[0, 1, 2, 3, 4]
```

- while
```
sum = 0
n = 99
while n > 0:
    sum = sum + n
    n = n - 2
print(sum)
```

- break:在循环过程中直接退出循环
- continue:提前结束本轮循环，并直接开始下一循环

# Intermediate Python
## 1.```*args``` 和 ```**kwargs```
```*args``` 是用来发送一个非键值对的可变数量的参数列表给一个函数.

```**kwargs``` 允许你将不定长度的键值对, 作为参数传递给一个函数.

## 2.生成器 Generators
- 可迭代对象 (Iterable)
- 迭代器 (Iterator)
- 迭代 (Iteration)
- 生成器 (Generators)

  
  ```iter``` 将可迭代对象返回迭代器：

```python
  my_string = "Yasoob"
  my_iter = iter(my_string)
  next(my_iter)
  # Output: 'Y'
```

## 3. ```Map``` 和 ```Filter```

###Lesson1
- Fixing Card Rank

```python
ranks = ['--123456789TJQKA'.index(r) for r, s in hand]
```

- Kind Function

```python
list.count(obj)
```

- Deal

  shuffle in random

```python
random.shuffle (lst)
# shuffle() 方法将序列的所有元素随机排序。
```

- Zip & Unzip

  zip() is defined; unzip is not defined but can be defined as:
```python
def upzip(group): return zip(*group)
```

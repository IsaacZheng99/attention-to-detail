# 注意细节

## 1. a // b 还是 int(a / b) ？

- 示例：

  ```python
  a = 10
  b = 3
  print(a // b)      # 3
  print(int(a / b))  # 3
  
  c = -10
  d = 3
  print(c // d)      # -4
  print(int(c / d))  # -3
  ```

- 原因 TODO

## 2. if not a or not b 还是 if not (a and b)

- 一般我们会判断a、b、c...是否都存在，后者会更好，因为只需要加两个单词。


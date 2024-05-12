# 4 Day

本次主要是学习一些数组操作。

## 优化

本次项目没有什么优化，只是我的代码风格和原作者不同。



## 我学到的新知识

- `console.table()` 可以以表格形式输出对象或数组。

- `reduce()` 方法将数组缩减为单个值，用法：

  ```js
  /**
   * @param total：必需。initialValue，或函数先前返回的值。
   * @param currentValue：必需。当前元素的值。
   * @param index：可选。当前元素的数组索引。
   * @param arr：可选。当前元素所属的数组对象
   *
   * @param initialValue：可选。作为初始值传递给函数的值。
  **/
  array.reduce(function(total, currentValue, currentIndex, arr), initialValue)
  ```

  项目中第四和第八题是 `reduce()` 例子。


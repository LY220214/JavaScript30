# 2 Day

## 优化：

- 添加 `user-select: none;` 提升体验。
- 添加时钟数字。（比想象中困难）
- 修改指针长度、宽度。（比想象中困难）
- 指针更线性的移动 `transition: all 1s`。
- 修复角度突变时，指针跳动。



## 我学到的新知识：

- 添加时钟数字使用了 `Grid` 布局。

- 设置 `transform: rotate(*deg)` 旋转元素。
- 设置 `transform-origin: 100%;` 设置旋转原点。
- `setInterval(function, milliseconds)` 方法会周期性调用函数，直到调用 `clearInterval()` 或关闭窗口。


# 3 Day

## 优化：

本次项目没有优化。

因为在我完成本次练习，并和原项目做对比后，原项目的写法让我惊叹。我的编码过于冗余，最后我通过学习原项目优化了自己的代码。



## 我学到的新知识

- 原来 `input` 标签的 `type` 选项还有 `range`（滑块控件）、`color`（拾色器）的选项。

- 设置标签的 `data-*` 属性，可在 `js` 中通过调用该 `DOM` 对象的 `dataset.*`  获取该属性的值。 

- 在 `css` 中可以使用 `--*` 来定义变量，该变量受级联约束，通过var(--*)调用。例子：全局自定义属性，并调用：

  ```css
  :root {
      --spacing: 1px;
      --blur: 0;
      --base: #ffc600;
  }
  
  img {
      padding: var(--spacing);
      filter: blur(var(--blur));
      background-color: var(--base);
  }
  ```

  在 `js` 中修改自定义属性的值需要通过 `setProperty(propertyname, value)` 方法修改：

  ```javascript
  document.documentElement.style.setProperty('--spacing', '10px')
  ```

- `css` 的 `filter` 属性，通常用于定义 `img` 的视觉效果，例如 `filter: blur(5px);` 可设置图片模糊效果。


# 5 Day

## 优化

- 添加 `user-select: none;` 提升体验。
- 循环添加事件在一个循环内完成。
- 修复了一个bug，原项目中的盒子在双击后，文字动画逻辑将会错误。

## 我学到的新知识

- `CSS` 中的 `flex` 属性：

  ```css
  flex: flex-grow flex-shrink flex-basis|auto|initial|inherit;
  ```

  本次主要是使用了 `flex-grow` 。该属性可以使 `flex` 布局中的盒子根据设定的 `flex-grow` 值，按比例增长。

  

- `classList.toggle(className, force)`:

  该方法用于在调用者的元素上添加或删除指定的 `className`。`className` 参数是必填的，而 `force` 参数是可选的。

  - 当 `force` 参数未提供时：`toggle()` 方法会在类列表中添加或删除指定的类名，并返回一个布尔值。如果类名已存在，则删除并返回 false；如果类名不存在，则添加并返回 true。
  - `force` 参数可以用来强制 `toggle()` 方法执行添加或删除操作，而不考虑类名是否存在。当 `force` 参数为 `true` 时，将强制添加类名；当 `force` 参数为 `false` 时，将强制删除类名。
  
- 媒体查询 `@media` ：

  可以根据不同条件使用不同 `css` 规则

  ```css
  @media media-type and (media-feature) {
      /* CSS 规则 */
  }
  ```

  例如，当屏幕宽度小于 600 像素时，段落文本颜色变为红色：

  ```css
  @media screen and (max-width: 600px) {
      p {
          color: red;
      }
  }
  ```

  


# 事件监听(绑定)

- 事件
  - 事件在编程时系统内部发生的动作或者发生的事情
  - 比如用户在网页上单击一个按钮
- 事件监听
  - 让程序检测是否有事情产生,一旦有事件触发,就立即调用一个函数做出响应,也成为绑定事件或者注册事件
  - 比如:鼠标经过显示下拉菜单,点击可以播放轮播图
  - 语法:

  ```txt
  元素对象.addEventListener('事件类型','要执行的函数')
  ```

  - 事件监听三要素
    - 事件源:那个dom元素被事件触发了,要获取dom元素
    - 事件类型:用什么方式触发,比如鼠标单击click,鼠标经过mouseover等
    - 事件调用的函数:要做什么事

  ```html
  <body>
    <button>按钮</button>
    <script>
      const btn = document.querySelector('button')
      //修改元素样式

      btn.addEventListener('click', function () {
        alert('点击了')

      })
    </script>
  </body>
  ```

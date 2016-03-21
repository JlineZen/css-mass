# CSS2.0 及 CSS3.0 的一些自己的见解

- direction
  属性值: ltr、 rtl;
  ltr: 从坐至右
  rtl: 从右至左
  ```css
    direction: ltr;
    direction: rtl;
  ```
  其中，ltr是left-to-right的简写，表示从左往右的意思，具体就是内联内容从左往右排列，按平时我们先出现dom，排列在左边;  
  rtl顾名思义，具体表示dom在前的出现在右边，而且是容器的最右边。  

  *注意：改变的只是内联块内容的顺序，而不改变行内元素的顺序，比如文字方向不改变。*

  + 什么是内联块元素？  
    就是display: inline-block的元素,比如 img, object, vedio, button, input等元素；
## js实现可拖拽的div ##


_说明_ ：

&emsp;&emsp;这是一个封装的js插件，接受两个参数

* 第一个：需要被点击拖拽的元素 bar
* 第二个：父元素wrap 


---
html

`<div class="wrap"><div class="bar"></div></div>`




css

`.wrap {position: absolute;}`



js

`dragBox(document.querySelector(".wrap"), document.querySelector(".bar"));`




***
#### 您也可以直接看代码示例 ###
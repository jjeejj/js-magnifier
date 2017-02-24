# js-magnifier
JS 图片放大镜

原理：

鼠标在小图片上移动时，捕捉鼠标在小图片上的位置，定位大图片的位置

对于下图片，移动的是放大镜
对于大图片，移动的是大图片本身

重点：
如何让小图片上的放大镜和大图片同步移动

用名词解释：

offsetLeft:相对与父元素的左位移
offsetTop:相对于父元素的顶部位移


offsetWidth和offsetHeight:是元素展示的宽度和高度，注意是不包括滚动条的

event.clientX和event.clientY是X和Y轴的坐标，相对于整个页面


offsetLeft和 style.left的区别(offsetTop和style.top一样的道理)：
不同点：
①：style.left返回的是字符串， offsetLeft返回的是数字，比如：30px: style.left ----> 30px ,offsetLeft ---->30
②：style.left是可读写的，ffsetLeft是只读的
③：style.left的值需要事先定义，只能取到在HtML中定义的样式，否者取到的值为空
相同点：




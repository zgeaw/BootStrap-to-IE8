#BootStrap-to-IE8
-------
# 32237384@qq.com


1、调用用法，在head中加入ie9以下兼容代码

#<!--[if lt IE 9]><script src="html5shiv.min.js"></script><link rel="stylesheet" href="ie8.css"><![endif]-->

2、文件说明
html5shiv.min.js（让IE8兼容HTML5标签,H5标签可以放心使用）

ie8.css（针对IE8单独写兼容类CSS，这个里面带bootstrap兼容方案）


3、让IE8支持CSS3部分属性，如圆角、投影等

ie-css3.htc

使用方法，在ie8.css中写入要兼容的class名，即可自动生效

.btn{behavior: url(ie-css3.htc);}

4、JQ兼容类库，版本1.9.1（可以完美兼容IE8与bootstrap等相关框架）

jquery.min.js
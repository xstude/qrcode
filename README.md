# qrcode

js二维码生成

## 综述

* 版本：1.0.0
* 浏览器支持： 所有浏览器
* 支持AMD,CMD
* demo: [http://backtonaturedemo.github.io/frontend/demo/qrcode/demo.html](http://backtonaturedemo.github.io/frontend/demo/qrcode/demo.html)
* 源地址: [https://github.com/davidshimjs/qrcodejs](https://github.com/davidshimjs/qrcodejs)

## 安装

    <script src="/path/to/qrcode.js"></script>
	// 或者
	var QRCode = require('qrcode.js');

## 使用方法

使用方法如下：

	<div id="qrcode"></div>
	var qrcode = new QRCode('qrcode', { // qrcode为id
		text: 'http://changyan.sohu.com',
		width : 100,
		height : 100
	});

还可以清除当前二维码或者生产新的二维码,用法如下：

	qrcode.clear(); // clear the code.
	qrcode.makeCode("http://naver.com"); // make another code.



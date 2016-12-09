## 让网页标题变得更有趣，效果类似于这种：https://www.nowcoder.com

当鼠标切换到其它选项卡的时候之前标签的标题就会发生变化，效果如下图所示：

!(visible)[https://github.com/BenDanChen/FunnyTitle/blob/HEAD/imgs/visible.png]
!(hidden)[https://github.com/BenDanChen/FunnyTitle/blob/HEAD/imgs/hidden.png]

### Usage:

1. 先引入jQuery文件，再引入funny-title.js
`
	<script src="js/jquery-3.1.1.min.js"></script>
	<script type="text/javascript" src="js/funny-title.js"></script>
`
2. 修改funny-title.js文件中的颜文字，改为自己需要的字符即可。
`
	document.title="(●—●)"+oldTitle;
`


注：如果浏览器皮肤颜色很深的话，再萌的表情也白瞎...

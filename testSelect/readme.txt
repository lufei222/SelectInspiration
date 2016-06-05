
在testSelect中主要完成的是一个div加ul和li的下拉选择框
实现的功能有：
1：任意指定div可以操作下拉框，取代原生的select，
手机端不支持select的size属性导致无法通过label或者div点击模拟select点击展开select的option的问题
问题在线链接http://www.w3school.com.cn/tiy/t.asp?f=html_select_size

手机端浏览器打开可以看出，size指定之后也是无效的，为此做过的此时如下代码
<html>
<body>

<p>这是段落。</p>
<p>这是段落。</p>
<p>这是段落。</p>
<select size="1" name="D1" id="test1">
  <option>1</option>
  <option>2</option>
  <option>3</option>
  <option>4</option>
</select>
<input type="button" value="提交" name="B1" onclick="if(test1.size==1){test1.size=test1.length} else{test1.size=1}">
</body>
</html>
上述代码在电脑浏览器是可以支持点击展开和收缩的，但是在手机端因为size的不支持所以是无效使用的

2：下拉框任意选中一个之后会对下拉div或者是当前的页面隐藏域赋值
如：目标元素<div id="divselect"value="">
	赋值方式$(divselect).attr("value",value);
	打印日志	console.log($(divselect).attr("value"))
3：直接使用idea打开默认的63342端口即可看到效果了，如果想在手机端页面看的话需要自己搭建node环境，
在我的github或者csdn
http://blog.csdn.net/u011456337/article/details/50704331
上面可以看到教程
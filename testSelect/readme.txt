
��testSelect����Ҫ��ɵ���һ��div��ul��li������ѡ���
ʵ�ֵĹ����У�
1������ָ��div���Բ���������ȡ��ԭ����select��
�ֻ��˲�֧��select��size���Ե����޷�ͨ��label����div���ģ��select���չ��select��option������
������������http://www.w3school.com.cn/tiy/t.asp?f=html_select_size

�ֻ���������򿪿��Կ�����sizeָ��֮��Ҳ����Ч�ģ�Ϊ�������Ĵ�ʱ���´���
<html>
<body>

<p>���Ƕ��䡣</p>
<p>���Ƕ��䡣</p>
<p>���Ƕ��䡣</p>
<select size="1" name="D1" id="test1">
  <option>1</option>
  <option>2</option>
  <option>3</option>
  <option>4</option>
</select>
<input type="button" value="�ύ" name="B1" onclick="if(test1.size==1){test1.size=test1.length} else{test1.size=1}">
</body>
</html>
���������ڵ���������ǿ���֧�ֵ��չ���������ģ��������ֻ�����Ϊsize�Ĳ�֧����������Чʹ�õ�

2������������ѡ��һ��֮��������div�����ǵ�ǰ��ҳ��������ֵ
�磺Ŀ��Ԫ��<div id="divselect"value="">
	��ֵ��ʽ$(divselect).attr("value",value);
	��ӡ��־	console.log($(divselect).attr("value"))
3��ֱ��ʹ��idea��Ĭ�ϵ�63342�˿ڼ��ɿ���Ч���ˣ���������ֻ���ҳ�濴�Ļ���Ҫ�Լ��node������
���ҵ�github����csdn
http://blog.csdn.net/u011456337/article/details/50704331
������Կ����̳�
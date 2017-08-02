EL 表达式(Expression Language):是为了简化jsp页面！替换Java小脚本

语法：${表达式}  这里的表达式 是作用域里面的key

基于四大作用域
pageContext
request
session
application

对应的是
pageScope
requestScope
sessionScope
applicationScope

之前向作用域赋值！

使用 .setAttribute("StringKey",ObjectValue)

我们只要把 任何需要的对象，放进作用域！
那么我们就可以使用EL表达式来获取我们存储的对象！

如果我们没有指定作用域！
会按照 pageScope==>>requestScope==>>sessionScope==>>applicationScope



我们的EL表达式多数情况下，是和JSTL标签联合使用的



JSTL  (JSP Standard Tag Library) jsp的标签库：是一个不断完善的jsp标签库

	core  format  xml  sql 

使用：	
	01.在需要的页面引入JSTL标签库
	02.使用标签


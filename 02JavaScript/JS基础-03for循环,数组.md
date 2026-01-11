# for循环
- for 循环语法
	```
	for(变量起始值;终止条件;变量变化量){
		//循环体
	}
	```
- 退出循环
	- continue 退出本次循环
	- break 退出整个for循环
- 循环嵌套
	```
	for(外部声明记录循环次数的变量;循环条件;变化值){
		for(内部声明记录循环次数的变量;循环条件;变化值){
			
			循环体
			
		}
	}
	```  
***
# 数组
- 声明语法
	```
	let 数组名 = [数据1,数据2,数据3,...,数据n]
	let arr = new Array(数据1,数据2,..,数据n)
	```  
- 遍历数组
	```
	for (let i = 0; i< 数组名.length;i++){
		数组名[i]
	}
	```
- 数组求和
	```html
	<script>
		
	let n = [2,6,1,7,4]
	s = 0
	for (var i = 0; i < n.length; i++) {
		s += n[i]
	}
	document.write(s)	

	//数组求和第二种办法
	console.log(n.reduce((a,b)=>a+b));

	</script>
	```

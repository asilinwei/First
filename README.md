- 相对于传统函数，IIFE有如下优势：
> 1. 封装变量防止全局污染。
  2. 实现Lazy Function提高性能。
>> ```javascript
	var a=2;
	var foo=(function(){
		if(a===1){
			return function(){
				console.log(1);
			}
		} else if(a===2){
				console.log(2);
		}
	})();
```
# First
## Second
### Third
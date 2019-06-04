### JavaScript 面试题
#### JS基础
1.jvascript 的 typeof 返回哪些数据类型<br/>
- 返回类型有**string类型、number类型、布尔类型、undefined类型、object类型、function类型、Symbol类型**七种类型。   
    object类型： `typeof null;`  
    function类型： `typeof isNaN;`   `typeof(Array);`  `typeof(Date);`   
    symbol类型（ES6提出的新的类型）： `typeof Symbol();` <br/>  
- 列举3种强制类型转换和2种隐式类型转换  
  强制类型转换：ParseInt()  ParseFloat() Number()  String() toString() Boolean();   
  隐式类型转换：`null == undefined //true`   `1 == "1"  //true`   <br />
- split() join()的区别  
  split():是将String对象切割成数组的形式  
  join():是将数组转换成字符串  <br />
- 数组方法pop() push() unshift() shift()
  unshift()：数组头部添加，返回新长度。  
  shift():数组头部删除，返回头部被删元素。   
  push():尾部添加，返回长度。  
  pop():尾部删除，返回元素。  
  
  
  
  



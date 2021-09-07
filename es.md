### tips

* Object.keys 
```
可以用来获取对象的key的集合，进而可以获得对应key的value
```
* 箭头函数
```
以前：
function fn () {}
const fn = function () {}

箭头函数：

const fn = () => {}
// 如果只有一个参数，可以省略括号
const fn = name => {}
// 如果函数体里只有一句return
const fn = name => {
    return 2 * name
}
// 可简写为
const fn = name => 2 * name
// 如果返回的是对象
const fn = name => ({ name: name })

普通函数和箭头函数的区别：

1、箭头函数不可作为构造函数，不能使用new
2、箭头函数没有自己的this
3、箭头函数没有arguments对象
4、箭头函数没有原型对象
```

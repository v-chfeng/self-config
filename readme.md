# 这是mark down语法的说明文档
1.标题
=====
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题

这是等号设置的大标题
=
这是"-"设置的中级标题
-
下面是一个横线
---
下面又是一个分割线
***

2.文本
===
## 普通文本
这是一段普通的文本，
直接回车不能换行，<br>
要使用\<br>
### 换行
需要两个空格接着换行  
上一句中“换行”后面有两个空格
隔一个空行也是换行，明显这个是段落换行
### 单行文本
    Tab后边跟文本就是一个单行文本
### 代码
`printf()` 函数
### 代码区块
``` json
{
    "hello": "value"
}
```
```javascript
$(document).ready(function () {
    alert('hello world!');
});
```
    function():
        return 'hello world!'

3.列表
===
#### 无序列表
* 1
* 2
* 3
+ 4
+ 5
- 6
- 7
#### 有序列表
1. 1
2. 2
3. 3

#### 列表嵌套
1. 第一项：
    - 第一项嵌套的第一个元素
        * 否定
    - 第一项嵌套的第二个元素
        * 肯定
2. 第二项：
    - 第二项嵌套的第一个元素
        1. a
        2. b
    - 第二项嵌套的第二个元素
4.字体
===
**粗体**   *斜体*  _斜体_  ~~删除线~~  
***粗体斜体***  ~~***粗体斜体删除线***~~  
\# 这是#的转义
<u>下划线借助html
  
  给段落加下划线
</u>

5.引用
===
> 这里是一个引用  
要注意符号和文本间的空格  
嵌套引用或者区块
> 第一级
>> 第二级
>>> 第三级

6.图片和链接
===
这是一个链接 <https://www.runoob.com/markdown/md-link.html>  
这是一个文本超链接 [Markdown 链接](https://www.runoob.com/markdown/md-link.html)
![alt 属性文本](图片地址)
![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png)

7.表格
===
|  表头居中   | 表头居左  | 表头居右  |
|  :----:  | :----  | -: |
| 单元格单元格单元格  | 单元格单元格单元格end | start单元格单元格单元格 |
| 单元格  | 单元格 |  |

8.流程图
=
flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
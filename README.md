# day19
- nodeName获取到的节点名是大写
> 1.document.getElementById（"id名称"）只能返回一个元素<br>
2.document.getElementsByName（"name名称"）[索引号] <br>
3.document.getElementsByTagName（"标签名称"）[索引号] <br>
4.document.getElementsByClassName（"类名称"）[索引号] <br>
以上后三种方法返回 **伪数组** 类型的数据 <br>
伪数组：具有数组的结构特点和相关属性但不具备数组的操作方式(只有一个符合也会返回数组类型) 
所以在使用以上三种方法的时候若只对一个元素进行操作，需要添加索引号找到对应的元素

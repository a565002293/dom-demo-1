##增
```
dom.create(string)//用于创建文本
dom.after(node, node2)//用于新增弟弟
dom.before(node, node2)//用于新增哥哥
dom.append(parent, node)//用于新增儿子
dom.wrap(node, parent) //用于新增爸爸
```
##删
```
dom.remove(node)//用于删除节点
dom.empty(node)//用于删除所有后代
```
##改
```
dom.attr(node, name, value)//用于改写属性
dom.attr(node, name)//用于读取属性
dom.text(node, string)//用于改写文本内容
dom.text(node)//用于读取文本内容
dom.html(node, string) //用于改写html内容
dom.html(node) //用于读取html内容
dom.style(node, name, value)
dom.style(node, object)//用于修改style
dom.style(node, name)用于读取style
dom.class.add(node, className)//用于添加class
dom.class.remove(node, className)//用于删除class
dom.class.has(node, className)//用于查询是否拥有该class
dom.on(node, eventName, fn)//用于添加事件监听
dom.off(node, eventName, fn)//用于删除事件监听
```
##查
```
dom.find(selector, scope)[index]//用于获取标签或标签们
dom.parent(node)//用于获取父元素
dom.children(node)//用于获取子元素
dom.siblings(node)//用于获取兄弟姐妹
dom.next(node)//用于获取弟弟
dom.previous(node)//用于获取哥哥
dom.each(nodeList, fn)//用于遍历所有节点
dom.index(node)//用于获取节点index
```
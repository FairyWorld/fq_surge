# surge
surge外部代理集链接：https://github.com/temppw/surge/raw/main/surge.list
添加链接到surge策略组-填入“外部代理集”里就行
节点已备注用途，可以用正则表达式过滤：
(A).*(B)             节点名既有 A又有 B 
(A)|(B)              节点名有 A 或者 B   
^((?!A).)*$或^(?!A).*   节点名不含有 A 
(?!.*(A)).*(B)         节点名不含有 A，同时含有 B
^(?!(.*(A|B).*))      节点名既不含有 A又不含有 B

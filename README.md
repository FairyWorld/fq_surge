TG频道：https://t.me/surgefree
# surge
surge外部代理集链接：https://github.com/temppw/surge/raw/main/surge.list

配置托管：https://github.com/temppw/surge/raw/main/surge.conf

添加链接到surge策略组-填入“外部代理集”里就行
### 订阅转换
list节点里加了一些参数，转换的时候不需要额外加参数了，例如emoji国旗。

转换后的链接：

clash：https://suo.yt/T4fbDrW

## 节点已备注用途，可以用正则表达式过滤：
(A).*(B)             节点名既有 A又有 B 
(A)|(B)              节点名有 A 或者 B   
^((?!A).)*$或^(?!A).*   节点名不含有 A 
(?!.*(A)).*(B)         节点名不含有 A，同时含有 B
^(?!(.*(A|B).*))      节点名既不含有 A又不含有 B

### 更新频率
每天不定期更新，为了保证高可用性会定期吧ping不通的节点剔除，避免过多节点导致性能下降。

### 节点源
https://github.com/v2raydy/v2ray

https://raw.githubusercontent.com/Jsnzkpg

为保证节点标识简洁，对大部分名称进行了重写。

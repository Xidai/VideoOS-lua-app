Data是OS_Lua系统中的 二进制数据组件。


## append
| api  |参数   |返回参数   |平台   |备注|
| ------------ | ------------ | ------------ | ------------ | ------------ |
|   append     |   v: Data/byte[]   |  -   |   -  | 新增部分数据  |

例:
```lua
Data("a"):append(Data(97, "abc", "def"))
```

## toString
| api  |参数   |返回参数   |平台   |备注|
| ------------ | ------------ | ------------ | ------------ |------------ |
|   toString   |  code: String    | v: String    |   -  |   转成String(编码格式)    |

例:
```lua
Data('a').toString("latin-1")
```

## toJson
| api  |参数   |返回参数   |平台   |备注|
| ------------ | ------------ | ------------ | ------------ |------------ |
|  toJson      |   -   |  v: String   |   -  |   转成Json String    |

例:
```lua
Data('{"a":"1"}').toJson()
```

## toTable
| api  |参数   |返回参数   |平台   |备注|
| ------------ | ------------ | ------------ | ------------ |------------ |
|    toTable    |   -   |  v: LuaTable   |   -  |   转成LuaTable    |

例:
```lua
Data('{"a":"1"}').toTable()
```




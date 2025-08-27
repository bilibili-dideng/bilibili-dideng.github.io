# 添加CA关键词

## 什么是CA关键词？

CA关键词就是CA扩展包的例如：`name`, `enmus`, `idlist`, `commands`  
在打开CA关键词树的时候就会有

## 如何添加CA关键词？

也是非常简单，示例：
```json5
{
  "name": "example-library",
  "description": "This is an example library for testing purposes.",
  "author": "Example Author",
  "uuid": "12345678-1234-123456789012",
  "version": "1.0.0",
  "ca_key": {
    "1": {
      "you_ca_keyword_name": {
        "name": "you_ca_keyword_name"
      },
      "you_ca_keyword_name-2": {
        "name": "you_ca_keyword_name-2"
      }
    },
    "2": {
      "you_ca_keyword_name-3": {
        "name": "you_ca_keyword_name-3"
      }
    }
  }
}
```

我们在`ca_key`下添加了一个`1`和`2`的键值对，还有3，4，他们分别对应：
-    1: "CA关键词",  
-    2: "参数类型",  
-    3: "命令属性",  
-    4: "参数属性"

里面的键值对就是我们要添加的CA关键词，格式是：
```json5
{
  "you_ca_keyword_name": {
    "name": "you_ca_keyword_name"
  }
}
```

其中`name`就是我们要添加的CA关键词的名称，这个名称会显示在CA扩展包的树中。
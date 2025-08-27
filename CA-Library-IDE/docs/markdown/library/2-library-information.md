# 扩展包信息

### 我们需要先配置一下信息：
**name** - 示例: `"name":"example-library"`  
**description** - 示例: `"description":"This is an example library for testing purposes."`  
**author** - 示例: `"author":"Example Author"`  
**uuid** - 示例: `"uuid":"12345678-1234-123456789012"`  
**version** - 示例: `"version":"1.0.0"`  

给一个示例：  
写过CA的拓展包的人应该都发现和这个差不多

```json
{
  "name": "example-library",
  "description": "This is an example library for testing purposes.",
  "author": "Example Author",
  "uuid": "12345678-1234-123456789012",
  "version": "1.0.0"
}
```

::: warning  
请不要把version写成例如：[1,0,0] 之类的！  
:::
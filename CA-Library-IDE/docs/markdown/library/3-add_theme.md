# 添加主题

## 什么是主题？

主题就是我们使用IDE时UI的配色

## 如何添加主题？

很简单，示例：
```json
{
  "name": "example-library",
  "description": "This is an example library for testing purposes.",
  "author": "Example Author",
  "uuid": "12345678-1234-123456789012",
  "version": "1.0.0",
  "theme": {
    "you_theme_name": {
        "primary_bg": "#2b2b2b",
        "secondary_bg": "#3c3f41",
        "accent": "#4b6eaf",
        "text": "#ffffff",
        "text_dim": "#cccccc",
        "border": "#555555",
        "item_hover": "#383838",
        "item_selected": "#4b6eaf",
        "string": "#a31515",
        "keyword": "#0000ff",
        "number": "#09885a",
        "key": "#116644",
        "brace": "#7F0055",
        "editor_bg": "#2b2b2b",
        "editor_text": "#dcdcdc"
    }
  }
}
```

在`theme`字段中，添加一个键值对，键为你想要的主题名称，值为一个对象，包含以下属性：

- `primary_bg`：主要背景色
- `secondary_bg`：次要背景色
- `accent`：强调色
- `text`：文本色
- `text_dim`：文本暗色
- `border`：边框色
- `item_hover`：鼠标悬停时项目背景色
- `item_selected`：选中项目背景色
- `string`：字符串颜色
- `keyword`：关键字颜色
- `number`：数字颜色
- `key`：键颜色
- `brace`：括号颜色
- `editor_bg`：编辑器背景色

这样，你就添加了一个新的主题了！

::: warning  
警告！请不要漏写任何属性，否则可能会导致IDE配色异常！  
:::
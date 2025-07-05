# FileMapping 的内置插件


## Folders


### `__dataFolders__`
- 参数名称: 数据文件夹
- 是否必须: 否
- 类型: str | list
- 默认值: None
- 描述: 
    - 用于申请一个数据文件夹
    - fileMapping 会在init时生成一个数据文件夹
    - 会返回申请的临时文件夹路径
    - 无法动态申请


### `__temporaryFolders__`

- 参数名称: 临时文件夹
- 是否必须: 否
- 加入版本: 0.3.15
- 类型: str | list
- 默认值: None
- 描述: 
    - 用于申请一个临时文件夹
    - fileMapping 会在init时申请一个临时文件夹, 并在插件结束时删除
    - fileMapping.temporaryFolders() 会返回申请的临时文件夹路径


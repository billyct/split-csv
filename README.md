# split-csv

根据配置文件来拆分当前文件夹下的 CSV 文件
CSV相关的处理，可使用：https://csvkit.readthedocs.io/en/latest/

### 编译
```
// 生成 「split-csv」 和 「split-csv.exe」 文件
make
```


### 使用说明

1. 新建文件夹
2. 新建 setting.csv
3. 放入需要拆分的 csv 文件
4. 将 split-csv 脚本拖入文件夹，双击运行


### 配置文件 setting.csv

记录数量 | 文件数量
------  | -------
2000    | 2
3000    | 1

如上表格的文件代表： 2000 行记录的文件 2 个，3000 行记录的文件 3 个


### ⚠ 注意
* 配置文件名称必须为「setting.csv」
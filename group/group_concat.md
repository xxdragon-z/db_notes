# group_concat的使用情况为：对type进行分组，type一样的列，将name合并到一起
* ### 基本语法
```
select type,group_concat(name) from table group by type
```
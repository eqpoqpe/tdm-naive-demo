# TDM Naive Demo

```
+-------------------------------+
|        [exec]                 |
| component -> le               |
|    |`- createState            |
|    |`- createState            |
|    |      |                   |
|    |      | [render]          |
| +- | ---- ` DOM --------------------+
| |  [User interface]           |     |
| |  |                          |     |
| |  |        [re-exec]         |     |
| |   `- setState -> le cmp old |     |
+ | ------------------- | ------+     |
  |                     | [re-render] |
  |                     ` DOM         |
  +-----------------------------------+
```

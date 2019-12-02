Python公共助手类
====
    这里收集工作中常用/快捷的静态方法整合成助手类


目录
----

列表类助手  

|       使用规则           |
| ------------------------------ |
| method_name(list_target , func_condition) |

具体静态方法列表

| 序号  |     方法      |           解          释       | 功能类似于 Python内置高阶函数 |
| :---: | :----------: | :------------------------------: | :------------------------------: |
| 1 | find_all() | 通用的查找某个条件的所有元素方法 | filter() |
| 2 | find_single() | 通用的查找某个条件的单个元素方法 | None |
| 3 | get_count() | 通用的计算满足某个条件的元素数量方法 | None |
| 4 | is_exists() | 通用的判断是否存在某个条件元素的方法 | None |
| 5 | sum() | 通用的求和方法 | sum() |
| 6 | select() | 通用的筛选方法 | map() |
| 7 | get_max() | 通用的获取最大元素方法 | max() |
| 8 | get_min() | 通用的获取最小元素方法 | min() |
| 9 | order_by() | 通用的升序排列方法 | sorted(,,reverse = False) |
| 10 | order_by_descending() | 通用的降序排列方法 | sorted(,,reverse = True) |
| 11 | delete_all() | 根据指定条件，删除元素 | None |

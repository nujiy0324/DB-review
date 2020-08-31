# Database Review

目前来看呢，我认为主要有以下九个部分

* **SQL**
* **E-R Model**
* **Buffer Management**
* **Relational Formalization**
* **XML？**
* **B+-Tree**
* **Query Processing**
* **Concurrency Control**
* **Aries Recovery <<< Transaction Log**

## SQL

1. 查询改写
2. relational algebra expression
3. group by
4. 排序 all 或者order by
5. 求和 sum
6. 基本的插入，修改语句

## E-R Model

应该选择一个关系作为中心，比如订单，details。

再看一下图例

## Relational Formalization

1. Canonical Cover （正则覆盖）
   1. 左边一样的直接合并
   2. 查看是否有冗余，拆分
2. Closure of attribute（属性闭包）
   1. 
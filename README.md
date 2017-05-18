# SMJPA
Spring data JPA+Spring mvc +mybatis+PageHelper ，实现跨数据库的同时，用JPA封装 新增 修改 删除操纵DML，复杂查询的话，JPA OR Mybatis

特点:


1）	实体类集成 BaseController<T>，一行代码解决一个通用的功能，新增  修改 删除(可以批量) ID查询，简洁优雅


2）	嵌入mybatis，可以轻松实现 复杂sql查询


3）	JPA+mybatis PageHelper 基本可以实现 跨数据库(分页问题解决，特殊函数就没办法了)


4）	支持根据实体类属性生成表字段功能，简化开发。而且封装了 新增修改功能，修改字段的时候只需要维护实体类属性就可以了。


5）	SpringDataJpa 支持按照方法名查询，也支持一般的分页查询，实在不想写，也可以拼sql实现 复杂查询，特别是在联级操作的时候，而不依赖mybatis

6）	支持自定义SQL的修改、删除，所以基本上 JPA可以完成所有的 DML操作，不需要借助 Mybatis

7）  主键是自定义生成的 用的是 java  32位的UUID，已经测试过 mysql 和 oracle都可以用的

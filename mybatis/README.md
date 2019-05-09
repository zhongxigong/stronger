# MyBatis是一个半ORM框架
# MyBatis使用
* 多数据源配置 
    * MyBatis多数据源配置
        * 创建多个`DataSource`
        * 根据 `DataSource`创建对应的`org.mybatis.spring.SqlSessionFactoryBean`对象。
            * 为model设置aliase, aliasePackage
            * 设置对应的 mybatis-mapper.xml
            * 设置configLocation
        * 创建 `MapperScannerConfigurer`
            * 设置对应的`SqlSessionFactory`
            * 设置mapper接口所在的包路径
* MyBatis最佳实践
    * 接口中包含操作db的方法和参数签名以及返回值
    * 在xml中写具体的sql。
* MyBatis增强实现
    * 在model上添加与数据库表以及字段的映射关系。
    * 在注解的帮助下可以将一些常用的curd的xml SQL给省略掉,极大的提升了开发效率。
    * 相关三方开源库 https://github.com/abel533/Mapper
    * https://github.com/baomidou/mybatis-plus
* 优秀插件
    * PageHelper 
    * 
* 事务配置 
# MyBatis原理
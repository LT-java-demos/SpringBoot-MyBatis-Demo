SpringBoot MyBatis Demo
===============

Create table `user` in mysql
```sql
CREATE TABLE user  (
  id bigint(20) NOT NULL AUTO_INCREMENT,
  name varchar(255)  DEFAULT NULL,
  age int(11) DEFAULT 0,
  PRIMARY KEY (`id`) USING BTREE
)
```

Run UserMapperTest

pom.xml
--------
```
<dependency>
    <groupId>mysql</groupId>
    <artifactId>mysql-connector-java</artifactId>
    <version>5.1.21</version>
</dependency>
<dependency>
    <groupId>org.mybatis.spring.boot</groupId>
    <artifactId>mybatis-spring-boot-starter</artifactId>
    <version>1.3.1</version>
</dependency>
```
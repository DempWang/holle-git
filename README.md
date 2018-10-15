# holle-git

## 第一天学习知识点

> 引用

### markdown

```java
@SpringBootApplication
public class Application {
}

```

git-day


spring 拦截器博客  
### 实现方式
1.注解 @Aspect  
2.继承Interceptor  

### 底层原理
jdk动态代理，
spring asm(cglib) 基于java字节码拦截

### 应用场景
1.基于aop实现日志拦截（需要实现）入参，返回结果，方法名，方法调用时长
2.基于aop实现权限控制
3.异常处理，ExceptionHandler
4.基于aop的cache处理

项目搭建起来，hello world

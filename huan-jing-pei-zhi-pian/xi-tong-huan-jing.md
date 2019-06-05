# 系统环境

系统环境包括应用所部署的宿主器的`PATH`信息，及`JVM`的相关信息。这两者的都可以通过`System`类获取。但是在`Han`中我们可以通过以下接口获取。

```java
public interface Environment{
    /**
     * 系统PATH信息
     * @return map
     */
    Map<String, Object> getSystemEnvironment();

    /**
     * Java运行环境信息
     * @return map
     */
    Map<String, Object> getJvmProperties();
}
```



**系统环境**

* 服务器环境

```text
System.getenv();
```

* Jvm运行环境

```text
System.getenv();
```


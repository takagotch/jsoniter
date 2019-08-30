### jsoniter
---
http://jsoniter.com/

.java
https://github.com/json-iterator/java

```java
// src/main/java/com/jsoniter/annotation/JsonWrapper.java

@Target((ElementType.ANNOTATION_TYPE, ElementType.METHOD))
@Retention(RetentionPolicy.RUNTIME)
public @interface JsonWrapper {
  JsonWrapperType value() default JsonWrapperType.BINDING;
}
```

```
```

```
```



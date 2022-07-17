## Java集合

### 介绍

在Java中，为开发者提供了集合框架，`java collections framework`,

我们可以把Java集合看成为一种容器，这个容器可以存放Java对象，对于Java中的基本数据类型（int、long、float等）需要包装成对应的对象类型后才能放到容器中；

![java_collections_overview.png](https://dd-static.jd.com/ddimg/jfs/t1/177003/34/27530/77150/62d39a5aE7ee11aaa/0e874aed3cdbe767.png)

Java容器中主要包括`Collection`和`Map`两种，这两个在Java中都是接口，

```java
public interface Collection<E>
  
public interface Map<K,V>
```

### Collection

#### List

#### Set

#### Queue

### Map

#### TreeMap

#### HashMap

#### HashTable

#### LinkedHashMap
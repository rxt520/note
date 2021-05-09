# 面试题 Java基础

1. 请聊一下Java 的集合类，以及在实际项目中的应用

- Collection
  - List
    - ArrayList
    - Vector
    - LinkedList
  - Map
    - TreeMap
    - HashMap
    - Hashtable
    - ConcurrentHashMap
  - Set
    - HashSet
    - TreeSet

2. 简述一下自定义异常的应用场景？
   1. 防止前端/调用方看到真实的错误信息
   2. 虽然JAVA给我们提供了丰富的异常类型,但是在实际的业务上,还有很多情况JAVA提供的异常类型不能准确的表述出我们业务上的含义
3. 描述Object 里常用的方法
   - toString 类的全限定名+@+对象的哈希码 ，可以进行重写
   - hashCode  返回该对象的hashCode值
   - equals 比较对象是否相等
   - wait 
   - notify
   - notifyAll
   - finalized GC 会调用该方法  自救
   - clone
4. JDK 1.8 的新特性 
   - Lambda表达式
   - 函数式接口
   - 方法引用和构造器调用
   - Stream API
   - 接口中的默认方法和静态方法
   - 新时间日期API






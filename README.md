# interview
面试集锦：收集各种面试题目，以及解题思路或者答案，解题技巧等等

#2017.11.19 整理面试题

##10道腾讯的Java面试题

1、说几种常见的攻击方式及预防手段。

2、http1.x和http2.x的区别。

3、mysql查询语句怎么做性能分析。

4、你知道哪几种排序算法？

5、HashMap和HashTable的区别，并说明其底层实现数据结构。

6、HashMap满了之后怎么扩容？

7、Linux中远程传输文件有什么方式？

8、说说Java中异常的分类。

9、TCP和UDP的区别，TCP为什么是三次握手，不是两次。

10、说说数据库设计的三范式，可以违反三范式吗？

##Dubbo面试题锦集

1、默认使用的是什么通信框架，还有别的选择吗?

2、服务调用是阻塞的吗？

3、一般使用什么注册中心？还有别的选择吗？

4、默认使用什么序列化框架，你知道的还有哪些？

5、服务提供者能实现失效踢出是什么原理？

6、服务上线怎么不影响旧版本？

7、如何解决服务调用链过长的问题？

8、说说核心的配置有哪些？

9、dubbo推荐用什么协议？

10、同一个服务多个注册的情况下可以直连某一个服务吗？

11、画一画服务注册与发现的流程图

12、集群容错怎么做？

13、在使用过程中都遇到了些什么问题？

14、dubbo和dubbox之间的区别？

15、你还了解别的分布式框架吗？

##Java List面试题汇总

1、你知道的List都有哪些？

2、List和Vector有什么区别？

3、List是有序的吗？

4、ArrayList和LinkedList的区别？分别用在什么场景？

5、ArrayList和LinkedList的底层数据结构是什么？

6、ArrayList默认大小是多少，是如何扩容的？

7、List是线程安全的吗？如果要线程安全要怎么做？

8、怎么给List排序？

9、Arrays.asList方法后的List可以扩容吗？

10、List和Array之间如何互相转换？

##Java Map集合面试题汇总

1、 你都知道哪些常用的Map集合?

2、Collection集合接口和Map接口有什么关系？

3、HashMap是线程安全的吗？线程安全的Map都有哪些？性能最好的是哪个？

4、使用HashMap有什么性能问题吗？

5、HashMap的数据结构是怎样的？默认大小是多少？内部是怎么扩容的？

6、怎么按添加顺序存储元素？怎么按A-Z自然顺序存储元素？怎么自定义排序？

7、HashMap的链表结构设计是用来解决什么问题的？

8、HashMap的键、值可以为NULL吗？HashTable呢？

9、HashMap使用对象作为key，如果hashcode相同会怎么处理？

10、HashMap中的get操作是什么原理？

##Spring面试题和答案（70道，史上最全）

1.什么是spring?

2.使用Spring框架的好处是什么？

3.Spring由哪些模块组成?

4.核心容器（应用上下文)模块。

5.BeanFactory–BeanFactory实现举例。

6.XMLBeanFactory

7.解释AOP模块

8.解释JDBC抽象和DAO模块。

9.解释对象/关系映射集成模块。

10.解释WEB模块。

11.为什么说Spring是一个容器？

12.Spring配置文件

13.什么是SpringIOC容器？

14.IOC的优点是什么？

15.ApplicationContext通常的实现是什么?

16.Bean工厂和Applicationcontexts有什么区别？

17.一个Spring的应用看起来象什么？

18.什么是Spring的依赖注入？

19.有哪些不同类型的IOC（依赖注入）方式？

20.哪种依赖注入方式你建议使用，构造器注入，还是Setter方法注入？

21.什么是Springbeans?

22.一个SpringBean定义包含什么？

23.如何给Spring容器提供配置元数据?

24.你怎样定义类的作用域?

25.解释Spring支持的几种bean的作用域。

26.Spring框架中的单例bean是线程安全的吗?

27.解释Spring框架中bean的生命周期。

28.哪些是重要的bean生命周期方法？你能重载它们吗？

29.什么是Spring的内部bean？

30.在Spring中如何注入一个java集合？

31.什么是bean装配?

32.什么是bean的自动装配？

33.解释不同方式的自动装配。

34.自动装配有哪些局限性?

35.你可以在Spring中注入一个null和一个空字符串吗？

36.什么是基于Java的Spring注解配置?给一些注解的例子.

37.什么是基于注解的容器配置?

38.怎样开启注解装配？

39.@Required注解

40.@Autowired注解

41.@Qualifier注解

42.在Spring框架中如何更有效地使用JDBC?

43.JdbcTemplate

44.Spring对DAO的支持

45.使用Spring通过什么方式访问Hibernate?

46.Spring支持的ORM

47.如何通过HibernateDaoSupport将Spring和Hibernate结合起来？

48.Spring支持的事务管理类型

49.Spring框架的事务管理有哪些优点？

50.你更倾向用那种事务管理类型？

51.解释AOP

52.Aspect切面

53.在SpringAOP中，关注点和横切关注的区别是什么？

54.连接点

55.通知

56.切点

57.什么是引入?

58.什么是目标对象?

59.什么是代理?

60.有几种不同类型的自动代理？

61.什么是织入。什么是织入应用的不同点？

62.解释基于XMLSchema方式的切面实现。

63.解释基于注解的切面实现

64.什么是Spring的MVC框架？

65.DispatcherServlet

66.WebApplicationContext

67.什么是SpringMVC框架的控制器？

68.@Controller注解

69.@RequestMapping注解

70.返回Json用什么注解？

##Zookeeper面试题锦集

1、zookeeper是什么框架？

2、有哪些应用场景？

3、使用什么协议？

4、说说分布式一致性算法Paxos

5、说一说选举算法及流程

6、zookeeper有哪几种节点类型？

7、zookeeper对节点的watch监听通知是永久的吗？

8、有哪几种部署模式？

9、集群中的机器角色都有哪些？

10、集群最少要几台机器，集群规则是怎样的

11、集群如果有3台机器，挂掉一台集群还能工作吗？挂掉两台呢？

12、集群支持动态添加机器吗？

13、zookeeper的java客户端都有哪些？

14、chubby是什么，和zookeeper比你怎么看？

15、说几个zookeeper常用的命令。

##阿里巴巴高级Java面试题（首发，70道）

1、java事件机制包括哪三个部分？分别介绍。

2、为什么要使用线程池？

3、线程池有什么作用？

4、说说几种常见的线程池及使用场景。

5、线程池都有哪几种工作队列？

6、怎么理解无界队列和有界队列？

7、线程池中的几种重要的参数及流程说明。

8、什么是反射机制？

9、说说反射机制的作用。

10、反射机制会不会有性能问题？

11、你怎么理解http协议？

12、说说http协议的工作流程。

13、http有哪些请求提交方式？

14、http中的200,302,403,404,500,503都代表什么状态？

15、http get和post有什么区别？

16、你怎么理解cookie和session，有哪些不同点？

17、什么是web缓存？有什么优点？

18、什么是https，说说https的工作原理？

19、什么是http代理服务器，有什么用？

20、什么是虚拟主机及实现原理？

21、什么是Java虚拟机，为什么要使用？

22、说说Java虚拟机的生命周期及体系结构。

23、说一说Java内存区域。

24、什么是分布式系统？

25、分布式系统你会考虑哪些方面？

26、讲一讲TCP协议的三次握手和四次挥手流程。

27、为什么TCP建立连接协议是三次握手，而关闭连接却是四次握手呢？为什么不能用两次握手进行连接？

28、为什么TCP TIME_WAIT状态还需要等2MSL后才能返回到CLOSED状态？

29、什么是DoS、DDoS、DRDoS攻击？如何防御？

30、描述一下Java异常层次结构。

31、什么是检查异常，不受检查异常，运行时异常？并分别举例说明。

32、finally块一定会执行吗？

33、正常情况下，当在try块或catch块中遇到return语句时，finally语句块在方法返回之前还是之后被执行？

34、try、catch、finally语句块的执行顺序。

35、Java虚拟机中，数据类型可以分为哪几类？

36、怎么理解栈、堆？堆中存什么？栈中存什么？

37、为什么要把堆和栈区分出来呢？栈中不是也可以存储数据吗？

38、在Java中，什么是是栈的起始点，同是也是程序的起始点？

39、为什么不把基本类型放堆中呢？

40、Java中的参数传递时传值呢？还是传引用？

41、Java中有没有指针的概念？

42、Java中，栈的大小通过什么参数来设置？

43、一个空Object对象的占多大空间？

44、对象引用类型分为哪几类？

45、讲一讲垃圾回收算法。

46、如何解决内存碎片的问题？

47、如何解决同时存在的对象创建和对象回收问题？

48、讲一讲内存分代及生命周期。

49、什么情况下触发垃圾回收？

50、如何选择合适的垃圾收集算法？

51、JVM中最大堆大小有没有限制？

52、堆大小通过什么参数设置？

53、JVM有哪三种垃圾回收器？

54、吞吐量优先选择什么垃圾回收器？响应时间优先呢？

55、如何进行JVM调优？有哪些方法？

56、如何理解内存泄漏问题？有哪些情况会导致内存泄露？如何解决？

57、从分布式系统部署角度考虑，分哪几层？

58、如何解决业务层的数据访问问题？

59、为了解决数据库服务器的负担，如何做数据库的分布？

60、什么是著名的拜占庭将军问题？

61、为什么说TCP/IP协议是不可靠的？

62、讲讲CAP理念。

63、怎么理解强一致性、单调一致性和最终一致性？

64、分布式系统设计你会考虑哪些策略？

65、最常见的数据分布方式是什么？

66、谈一谈一致性哈希算法。

67、paxos是什么？

68、什么是Lease机制？

69、如何理解选主算法？

70、OSI有哪七层模型？TCP/IP是哪四层模型

##关于String的10道经典面试题

1、String是基本数据类型吗？

2、String是可变的话？

3、怎么比较两个字符串的值一样，怎么比较两个字符串是否同一对象？

4、switch中可以使用String吗？

5、String str = new String("abc");创建了几个对象，为什么？

6、String、StringBuffer、StringBuilder有什么区别？

7、String.trim()方法去掉的是哪些字符？

8、String可以被子类继承吗？

9、可以自定义java.lang.String类并使用吗？

10、String与byte[]两者相互之间如何转换？

##去BAT面试完的Mysql面试题总结（55道，带完整答案）

1、一张表里面有ID自增主键，当insert了17条记录之后，删除了第15,16,17条记录，再把mysql重启，再insert一条记录，这条记录的ID是18还是15 ？

2、mysql的技术特点是什么？

3、Heap表是什么？

4、mysql服务器默认端口是什么？

5、与Oracle相比，mysql有什么优势？

6、如何区分FLOAT和DOUBLE？

7、区分CHAR_LENGTH和LENGTH？

8、请简洁描述mysql中InnoDB支持的四种事务隔离级别名称，以及逐级之间的区别？

9、在mysql中ENUM的用法是什么？

10、如何定义REGEXP？

11、CHAR和VARCHAR的区别？

12、列的字符串类型可以是什么？

13、如何获取当前的mysql版本？

14、mysql中使用什么存储引擎？

15、mysql驱动程序是什么？

16、TIMESTAMP在UPDATE　CURRENT_TIMESTAMP数据类型上做什么？

17、主键和候选键有什么区别？

18、如何使用Unix shell登录mysql？

19、 myisamchk是用来做什么的？

20、mysql数据库服务器性能分析的方法命令有哪些?

21、如何控制HEAP表的最大尺寸？

22、MyISAM Static和MyISAM Dynamic有什么区别？

23、federated表是什么？

24、如果一个表有一列定义为TIMESTAMP，将发生什么？

25、列设置为AUTO　INCREMENT时，如果在表中达到最大值，会发生什么情况？

26、怎样才能找出最后一次插入时分配了哪个自动增量？

27、你怎么看到为表格定义的所有索引？

28、LIKE声明中的％和_是什么意思？

29、如何在Unix和mysql时间戳之间进行转换？

30、列对比运算符是什么？

31、我们如何得到受查询影响的行数？

32、mysql查询是否区分大小写？

33、LIKE和REGEXP操作有什么区别？

34、BLOB和TEXT有什么区别？

35、mysql_fetch_array和mysql_fetch_object的区别是什么？

36、我们如何在mysql中运行批处理模式？

37、MyISAM表格将在哪里存储，并且还提供其存储格式？

38、mysql中有哪些不同的表格？

39、ISAM是什么？

40、InnoDB是什么？

41、mysql如何优化DISTINCT？

42、如何输入字符为十六进制数字？

43、如何显示前50行？

44、可以使用多少列创建索引？

45、NOW（）和CURRENT_DATE（）有什么区别？

46、什么样的对象可以使用CREATE语句创建？

47、mysql表中允许有多少个TRIGGERS？

48、什么是非标准字符串类型？

49、什么是通用SQL函数？

50、解释访问控制列表

51、mysql支持事务吗？

52、mysql里记录货币用什么字段类型好？

53、mysql数据表在什么情况下容易损坏？

54、mysql有关权限的表都有哪几个？

55、mysql中有哪几种锁？

##稍微有点难度的10道java面试题

1、jvm对频繁调用的方法做了哪些优化？

2、常见的攻击手段有哪些？如何防范？

3、restful api有哪些设计原则？

4、hessian是做什么用的？它的传输单位是什么？

5、http中的post、get有什么区别？base64过后的字符串可以通过get传输吗？

6、常用的算法都有哪些分类，分别有哪些算法及应用场景？

7、死锁是什么？写一个死锁的例子？如何避免死锁？

8、学用的序列化方案都有哪些，说说它们的优缺点？

9、什么是过滤器、拦截器、监听器，它们的顺序是怎样的？

10、servlet3.0有哪些新规范？


<img src="https://img-blog.csdnimg.cn/20210530112848298.jpg" alt="img" style="zoom:50%;" />
<br/>
一年一度的秋招大戏又快拉开序幕了，近年来后端岗位越来越卷，毕业生的压力也越来越大。个人感觉目前各个大中厂校招面试不好的地方是，都在朝着背面试八股文的方向发展（曾经面试某二线厂，对着面试官纯背了 40 分钟概念），但不得不承认这也是企业在短时间内筛选面试者的一个重要手段。

为了帮助大家了解后端面试八股文应该怎么背，特此推出面试八股文画重点系列（包含的内容有 `Java 基础`、`JVM`、`MySQL`、`Redis`、`操作系统`、`计算机网络`、`设计模式`）。希望能帮助到 Java 基础不是很好的同学能快速的准备好面试八股文。另外，希望大家背好面试八股文以后，还是要对底层原理多理解，如果在面试中你能自然的根据面试官的问题抛出一些你对相关底层原理的理解，面试官会特别惊喜的。

另外也要多了解这些知识点在实际场景中的应用。我比较喜欢的一种面试形式是，面试官出一个场景，然后让你设计方案去解决这个具体问题。如果你能根据你的所学，以恰当方式解决了面试官的问题，并且能分析清楚为什么这样做，对你的面试是非常加分的。我就曾经在京东的主管面中，选择了最合适的数据结构（用了`布隆过滤器`的思想）解决了面试官的场景题，主管直接就把 `Special offer` 给我了。

**面试技巧**

在这里穿插一个面试技巧，因为这是八股文的开篇，就多讲一点。大家在准备面试的时候不是要把网上所有面经的问题都背会，网上那么多问题你也不可能背会。首先你在准备秋招的时候要定一个计划，计划好你哪一部分要准备到什么程度。比如我的计划就是下面这样：

1. Java 基础

` Java` 要熟悉，在校招面试中的问题90%要回答上来。将 `HashMap`、`ArrayList` 等集合重点准备，将并发中的 `线程池`、`锁机制` 等重点理解，面试官问的时候我尽量答出点他在其它面试者那不常听到的东西。

2. JVM

`JVM` 调优不学，其它的常见问题都要做到回答清楚。

3. MySQL

`MySQL` 重点准备。除了 MySQL 的常见问题要会，对于 MySQL 的优化要有一定的积累，这里的 MySQL 优化技巧不止局限于面经，要给面试官来点面应届生的时候不常听到的。MySQL 后来也一直是我在面试的时候的爆点，曾经一个大厂的面试官和我聊了一阵 MySQL 以后还问我是怎么把这里学的这么好的。在这里推荐一个课程，是林晓斌的MySQL实战45讲，我从这门课上学到了挺多的东西。因为这个课是收费课程，他们也没找我做广告，就不挂链接了，你们感兴趣的自己找哈~

4. Redis

`Redis` 重点准备。大家对 Redis 的准备可能就是背 Redis 的几种数据类型、Redis为什么那么快、Redis的持久化机制、什么是缓存击穿、什么是缓存穿透、什么是缓存雪崩、什么是快乐星球？嗯...我比你们多准备了点，我看着`《Redis的设计与实现》`这本书把 Redis 的数据结构充分理解了、充分理解了 Redis 的持久化、也充分理解了 Redis 的集群设计，并且把集群带到了我的项目中，并且利用集群的特性对项目做了一定的优化。这里也是我面试的杀招。

![](https://img-blog.csdnimg.cn/20210603204627820.png)


5. 计算机网络、操作系统、组成原理

这些上面少花时间。根据自己的一些基础，加上用一两天时间把网上的诸如三次握手四次挥手的面经八股文背了背就好了。面试官问的时候大大方方说这里只懂一些最基础的就好了。

6. 项目、设计模式

项目我准备了两个，一个是电商项目，一个是实现简化版的Spring框架的项目。电商项目就是通用的 Nginx + Redis + RabbitMQ + MySQL的架构，不过我通过自己对 Redis 和 MySQL 的理解，在这些环节做了自己的优化。另一个项目是实现简化版 Spring 框架，反射、注解、设计模式这些都在项目上应用了。面试官问我设计模式的时候，我说我就熟项目里用的几种设计模式。

这样，自己的知识体系就准备好了，其实通过上面计划的制订，自己的简历也写出来了。从面试开始，自我介绍这个环节，就要把面试官往自己熟悉的地方去引，一旦面试官问出你预先做个详细准备的问题，我能给他讲到他下班。

另外，回答问题前想清楚，在回答一个问题时，千万不要提到另一个你不熟的东西。你一提到另一个东西，就相当于给面试官提了个醒让面试官追问，这个东西如果你又不熟，你不是给自己挖个大坑吗？

## 如何准备Java面试八股文

好了，前面多说了点，现在回到这篇文章的主题，现在这个环境，八股文是肯定要背一些的。大白，来给面试官整个活，把面试八股文背起来~

如何准备才能对着面试官熟练的背诵 Java 面试八股文？需要两步准备！

（1）准备秋招前期，看着书籍学习 Java 基础知识。

（2）准备秋招后期，在对 Java 基础知识有一定掌握的情况下，根据面试常考知识点来背诵面试八股文。

### 秋招前期准备

这时，应该在大厂秋招开始前的 2-3 个月左右，推荐大家跟着《Java 编程的逻辑》来学习 Java 基础知识。这个阶段 Java 基础弱的同学应该好好把握住。趁还有时间，边看书边把书中的实例跟着敲一敲，把书中的技术都用一用，体会一下 Java 的编程思想。

推荐理由：这本书真正做到了深入浅出的讲解 Java 知识，内容有深度，但描述通俗易懂。极力推荐。

![](https://img-blog.csdnimg.cn/20210602212959918.png)

#### 学习内容：

学习内容按照《Java 编程逻辑》的目录进行介绍。

**第 1 章：编程基础**

这一章的学习内容有，数据类型和变量、赋值、基本运算、条件执行、循环、函数用法、函数调用基本原理。这些都是 Java 最基础的，肯定要会。

**第 3 章：类的基础、第 4 章：类的继承、第 5 章：类的扩展**

这里是面试的高频考点。封装、继承、多态三大特性，重载、重写，哪些可以被继承、哪些不可以被继承等等经常会被面试官问到。所以这三章要认真的学习。多体会面向对象的编程思想，也能帮助大家写出高质量的代码。

**第 6 章 异常**

这块不用学的太细，但是基础的把异常捕获抛出是要学会的，写代码也经常要用。对常见异常类型要掌握。

**第 7 章 常用基础类**

`String` 相关的好好看一下，不止对 `String` 的概念要熟，对 `String` 的操作也要熟。虽然面试的手撕代码过程中大部分面试官是允许你查 API 的，但是涉及到 `String` 的操作还是尽量别查了，面试官可能会觉得你平常的代码量太少了。其它的常用基础类基本了解就好。

**第 9 章->第 12 章 集合部分**

集合部分是 Java 后端面试的一个超高频考点。`ArrayList`、`LinkedList`、`HashMap`、队列的操作要熟练，写代码题时经常要用到这几个容器。另外对上述几个集合的实现原理，所采用的数据结构要了解清楚，也要体会一下这些集合设计的好在哪里。

**第 15 章、第 16 章、第 17 章、第 19 章、第 20 章 并发部分**

并发部分是各个大厂面试的超高频考点。常问的考点有线程的基本概念、`Synchronized`、线程的协作机制、`CAS`、`ReentrantLock`、`ConcurrentHashMap`、线程池。要充分理解上述知识点的实现思想，并且记牢这些知识点的工作流程。另外最好能看一些上述考点在实际场景中的应用。如果能把这些技术恰当的应用在你的项目里，并解决了实际问题，面试官会比较惊喜的。

**第 21 章 -> 第 24 章**

反射、注解、动态代理、类加载机制

这快如果有时间的话学一下，然后结合着 `Spring` 的实现原理进行回答，可以当作你面试的亮点。

### 秋招准备后期

经过前面 Java 基础知识的学习，我们已经基本掌握了 Java 基础知识，这时各个大厂的秋招简历通道陆续开放了，想要了解各个大厂秋招的招聘流程和面试特点，请参考我的另一篇文章，“为了揭开互联网大厂秋招内幕，我把他们全面了一遍”。

现在我们要开始针对性的背面试八股文了！背面试八股文要推荐一个必看的开源项目（学 Java 基础以及实战也推荐看这个项目），他就是大名鼎鼎的 JavaGuide，Guide 哥！YYDS！

<img src="https://img-blog.csdnimg.cn/20210529184126262.png" alt="img" style="zoom: 33%;" />
<br/>

我针对 **JavaGuide** 上的内容给大家画一下重点并做一下说明，大家可以有针对性的去看。下面问题的答案都在 JavaGuide 中能找到。链接如下：

https://snailclimb.gitee.io/javaguide/#/?id=%e5%9f%ba%e7%a1%80

下面的知识点都是要看的，我通过打星与加粗的方式对知识点的重要性进行评级！难度是针对互联网大厂的。

一星：面试中不常问到，如果面试官问到尽量能答出来，答不出来也没关系。

二星：面试中不常问到，但是如果面试官问到的话，答不出来对你的印象会减分。

三星：面试中会问到，答不出来面试有点悬。面试官会惊讶为什么你这也不会。

四星：面试高频考点。

五星：面试超高频考点。四星考点和五星考点是参加十场面试，至少能有五场面试问到这些的。大家在准备面试过程中尽量把这些知识点的回答条理梳理清楚，面试官一问就开背。

1.Java 语言的特点（如果你简历上有提到 C++ 可能还会问你 Java 和 C++ 的区别）。【⭐⭐】

2.比较 JVM 和 JDK 以及 JRE 。【⭐⭐】

3.为什么说 Java 语言“解释与编译并存”。【⭐⭐】

4.Java 基本类型有哪几种，各占多少位？【⭐⭐】

前些年面试常问的一个问题，去年面试过程中只京东问我了

5.Java 泛型，类型擦除。【⭐】

6. `==` 和 `equals()` 的区别。【⭐⭐⭐】

这个问题在 2018 年之前几乎是面试必问的问题，但是现在大厂以及比较少问了，现在小厂中厂问的多。

7.**`hashCode()` 和 `equals()`** 【⭐⭐⭐⭐】

这个问题经常问，面试官经常问为什么重写 `equals()` 时要重写 `hashCode()` 方法？

这个问题经常结合着 `HashSet` 问。

8.**重载和重写的区别。** 【⭐⭐⭐⭐】

9.深拷贝和浅拷贝。【⭐】

10.面向对象和面向过程的区别。【⭐⭐⭐】

11.成员变量与局部变量的区别。【⭐⭐⭐】

12.面向对象三大特性是什么。并解释这三大特性。【⭐⭐⭐】

13.**`String`、`StringBuffer` 和 `StringBuilder` 的区别。** 【⭐⭐⭐⭐】

14.异常。【⭐⭐⭐】

不会问的特别细。经常的问法是异常可以分为哪几种，然后你答了可检查异常和不可检查异常以后，会让你举例可检查异常有哪些，不可检查有哪些。

然后异常的代码要会写，有一场字节的面试，直接让我写一个把异常捕获了然后抛出去的代码。

15.序列化和反序列化【⭐⭐】

16.`List`、Set`、` `Map` 的区别。【⭐⭐】

17.**`ArrayList` 和 `LinkedList` 的区别。**【⭐⭐⭐⭐】

答清楚每个分别采用什么数据结构，对比相应的优点和缺点。

18.**`HashMap`、`HashTable`、以及 `ConcurrentHashMap` 的区别。**【⭐⭐⭐⭐⭐】

现在面试的超高频考点。当面试官问到这个问题的时候，展现你背面试八股文能力的机会来了。

你可以展开去讲在 Java7 和 Java8 中 `HashMap` 分别采用什么数据结构，为什么 Java8 把之前的`头插法`改成了`尾插法`，怎样实现`扩容`，为什么`负载因子`是 `0.75`，为什么要用`红黑树`等等一系列的东西。只要面试官不打断我，我在这个知识点上能背到面试官下班。我最近也准备写一篇文章，详述上述知识点。

19.进程和线程的区别。【⭐⭐⭐⭐⭐】

这是一个超高频考点，面试回答时别一句一个进程包含很多线程就没了。

要答清楚什么是线程什么是进程，线程和进程各自的`运行状态`、线程的`通信方式`和进程的`通信方式`。

20.创建线程的方式。【⭐⭐⭐⭐】

不仅要把创建线程的方式记熟、记住各种方式的优缺点，还要能写出代码来。有的面试官是会让你写代码创建两个线程然后执行一些操作的，比如两个线程交替输出数字。

21.什么是死锁，死锁如何产生，死锁如何避免。【⭐⭐⭐⭐⭐】

超高频问题，几乎大厂的一面和二面都会问到。

22.`synchronized` 锁升级流程。【⭐⭐⭐⭐⭐】

这又是面试八股文的一大考点，锁升级流程记清楚。

23.`volatile` 关键字。【⭐⭐⭐⭐⭐】

对比和 `synchronized` 的区别。

24.乐观锁和悲观锁的区别。【⭐⭐⭐⭐⭐】

25.`ThreadLocal`。【⭐⭐⭐⭐】

这也是面试八股文的一个高频考点。我面试到后面不想背这里了，面试过程中就尽可能躲着这个知识点，不提到和这相关的，竟然真的苟过去了。

26.线程池。【⭐⭐⭐⭐⭐】

超高频考点。需要答出线程池有哪几种，各种线程池的优缺点，线程池的重要参数、线程池的`执行流程`、线程池的饱和策略、如何设置线程池的大小等等。这里也能背十几分钟。

27.`ReentrantLock` 和 `AQS`。【⭐⭐⭐⭐】

其实我在面试的时候对这里不是很熟，我面试的时候尽量不提到这里，也苟过去了。大家如果时间充足的话还是把这块好好理解一下。如果这里理解透彻了，也能在这里和面试官聊很久。
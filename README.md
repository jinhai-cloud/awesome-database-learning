# Awesome Database Learning

A curated reading list about database systems, inspired by:
- [pingcap / awesome-database-learning](https://github.com/pingcap/awesome-database-learning)
- [编程小梦 / 数据库学习资料](https://blog.bcmeng.com/post/database-learning.html)
- [CMU Database Courses](https://db.cs.cmu.edu/courses/)

## Query Optimizer

Blogs:
- [数据库查询优化器初探](https://mp.weixin.qq.com/s/VEK3V7zEULBPhAsKv1JENQ)

### Planner

Blogs:
- [SQL 查询优化原理与 Volcano Optimizer 介绍](https://zhuanlan.zhihu.com/p/48735419)

Papers:
- [The Volcano Optimizer Generator: Extensibility and Efficient Search](https://15721.courses.cs.cmu.edu/spring2020/papers/19-optimizer1/graefe-icde1993.pdf)
- [The Cascades Framework for Query Optimization](https://15721.courses.cs.cmu.edu/spring2020/papers/19-optimizer1/graefe-ieee1995.pdf)
- [Efficiency in the Columbia Database Query Optimizer](https://15721.courses.cs.cmu.edu/spring2020/papers/20-optimizer2/xu-columbia-thesis1998.pdf)
- [Orca: A Modular Query Optimizer Architecture for Big Data](https://15721.courses.cs.cmu.edu/spring2020/papers/19-optimizer1/p337-soliman.pdf)

### Subquery

Blogs:
- [SQL 子查询的优化](https://zhuanlan.zhihu.com/p/60380557)
- [Calcite 子查询处理 - RemoveSubQuery](https://zhuanlan.zhihu.com/p/62338250)
- [Calcite 子查询处理 - Decorrelate](https://zhuanlan.zhihu.com/p/66227661)

### Window

Blogs:
- [SQL 窗口函数的优化和执行](https://zhuanlan.zhihu.com/p/80051518)

Papers:
- [Efficient Processing of Window Functions in Analytical SQL Queries](http://www.vldb.org/pvldb/vol8/p1058-leis.pdf)
- [Optimization of Analytic Window Functions](http://vldb.org/pvldb/vol5/p1244_yucao_vldb2012.pdf)


## Query Execution

Blogs:
- [SQL 查询的分布式执行与调度](https://zhuanlan.zhihu.com/p/100949808)

### Vectorization vs Compilization

Blogs:
- [表达式编译](https://zhuanlan.zhihu.com/p/51221350)
- [查询编译](https://zhuanlan.zhihu.com/p/58249033)

Papers:
- [Vectorization vs Compilation in Query Execution](https://15721.courses.cs.cmu.edu/spring2020/papers/16-vectorization2/p5-sompolski.pdf)
- [MonetDB/X100: Hyper-Pipelining Query Execution](https://www.cidrdb.org/cidr2005/papers/P19.pdf)
- [Efficiently Compiling Efficient Query Plans for Modern Hardware](https://www.vldb.org/pvldb/vol4/p539-neumann.pdf)
- [Everything You Always Wanted to Know About Compiled and Vectorized Queries But Were Afraid to Ask](http://www.vldb.org/pvldb/vol11/p2209-kersten.pdf)

### Join

Blogs:
- [Join 查询优化](https://zhuanlan.zhihu.com/p/580164199)
- [Join Reorder 源码解析](https://zhuanlan.zhihu.com/p/579978445)

Papers:
- [Performance and Scalability of Broadcast in Spark](https://www.mosharaf.com/wp-content/uploads/mosharaf-spark-bc-report-spring10.pdf)
- [Adaptive Optimization of Very Large Join Queries](https://db.in.tum.de/~radke/papers/hugejoins.pdf)
- [SAHA: A String Adaptive Hash Table for Analytical Databases](https://www.mdpi.com/2076-3417/10/6/1915/htm)

Courses:
- [Join查询优化&HashJoin算子优化](https://www.bilibili.com/video/BV1bi4y1r7Td/)


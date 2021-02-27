学习笔记

# 第1课时

<img src="https://github.com/MrKID/JAVA-01/blob/main/Week_01/%E7%AC%AC1%E8%8A%82%E8%AF%BE/classLoadModel.png" />

# 第2课时

## JVM有哪些工具？

### 1、命令行工具

jarsijava、javac、javap、javadoc、javah、extcheck、jdb、jdeps、jar、keytool、jarsigner、policytool、jps/jinfo、jstat、jmap、jstack、jcmd、jrunscript/jjs

### 2、图形化工具

jconsole、jvisualvm、VisualGC、jmc

## GC的相关基础知识

### 1、GC的背景与一般原理

为什么需要GC？因为内存资源是有限的，因此需要手动申请，手动释放

清除算法，整理算法和复制算法的异同

### 2、常见的GC算法

串行GC（Serial GC）/ ParNew GC

并行GC（Parallel GC）

CMS GC / G1GC


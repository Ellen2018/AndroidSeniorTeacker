# Android高级工程师

以文章形式分析每个专题。均带实战演练,这是笔者接下来的学习路线:

## Android部分

- 1.Handler机制 & 导致泄漏的真正原因？
- 2.View绘制机制，事件分发，事件分发流程监控
- 3.Vsync信号与卡顿原因 & 监控与排查
- 4.ANR的原理与监控排查
- 5.SurfaceView它适合用来干什么？
- 6.布局性能监听工具分析与打造
- 7.冷启动 & 温启动 & 热启动，如何统计时间 & 优化
- 8.Android实现动画的原理 & 矢量动画SVG & 矢量动画框架Lottie
- 9.实现美团技术方案:WebView的优化 
- 10.apk里都有些什么，如何进行瘦身优化？
- 11.ViewPager & ViewPager2结合Fragment使用卡顿原因，懒加载有哪些方案？
- 12.App多进程开发 & AIDL & 其他进程间通信方案与使用场景
- 13.业务架构全解析，如何选择合适的架构
- 14.内存泄漏的检测与修复，常见的内存泄漏有哪些？
- 15.RecyclerView的原理 & 几层缓存 & LayoutManager与自定义。
- 16.那些使用了APT的框架，APT实战模拟ButterKnife。
- 17.字节码插桩技术，哪些框架使用了它？用它完成登录案例的切面编程
- 18.类加载机制，热修复与插件化原理与实践。
- 19.自定义View的几种方式 & 自定义属性 & View坐标系 & View绘制 & View分发
- 20.借助RecyclerView原理打造可复用的流式布局
- 21.借助RecyclerView原理打造可复用的表格控件
- 22.秒切换肤方案:网易云换肤的原理与实践
- 23.架构设计:使用设计模式打造一款数据库语句构建轮子
- 24.用APT打造一款基于SQLite的轮子
- 25.Service & 进程保活全方案分析
- 26.线上Crash & 卡顿 & ANR 监听方案解析
- 27.优雅埋点方案全解析
- 28.何为Hock技术？
- 29.线程优化，如何控制App的线程数量从而对电量进行优化。
- 30.跨进程传递大数据量数据，例如大图片，怎么办？
    
## Framework开发

- 1.系统启动流程
- 2.App启动流程
- 3.Activity启动流程
- 4.Service启动流程
- 5.进程间通信方案有哪些？为什么Zygote采用Socket进行进程间通信，其它进程间通信采用Binder？
- 6.Binder通信的原理
- 7.Framework开发:封装进程间通信SDK
- 8.Handler的屏障消息是什么？异步消息又是什么？
- 9.AMS & PMS & WMS 是什么？
- 10.Vsync信号是什么？它工作的原理是什么，卡顿的原因是什么？
- 11.站在Android系统角度去理解Context
- 12.Activity显示的原理，View树具体显示是在onCreate生命周期之后吗？
- 13.系统广播的工作原理？
- 14.ContentProvider的工作原理
- 15.app安装过程 & 增量更新原理
- 16.SurfaceView和View的区别？   
- 17.Handler的原理 & Looper死循环为什么不会导致应用卡死？
- 18.Handler中何为屏障消息，何为异步消息？
- 19.什么是IdleHandler?
- 20.App启动流程中ApplicationThread和ActivityThread的区别与作用？
- 21.dex和class文件区别
- 22.Dalvik虚拟机和ART虚拟机区别

## Java部分

- 1.Java集合的原理:ArrayList & LinkedList & HashMap & ConcurrentHashMap
- 2.Java线程 & 线程池
- 3.synchronized & Lock锁的原理  
- 4.cas,aqs,栅栏,ThreadLocal,volatile原理
- 5.类加载器，双亲委托，Android的热修复原理
- 6.Java泛型 & 原理
- 7.Java注解 & 反射注解
- 8.即时编译和预前编译
- 9.JVM内存结构
- 10.对象的生命周期
- 11.JMM[原子性 & 重排序 & 可见性]
- 12.虚拟机加载class的过程
- 13.字节码插桩是什么技术？Android中如何进行字节码插桩

## 数据结构与算法部分

- 1.空间复杂度 & 时间复杂度
- 2.数组 & 动态数组
- 3.单链表 & 双向链表 & 循环链表
- 4.栈
- 5.队列
- 6.树 & 遍历 & 完全二叉树 & 平衡二叉树
- 7.排序算法:冒泡 & 选择 & 插入 & 快排
- 8.查找算法:二分查找 & 跳表
- 9.其他算法:LeetCode刷题

## 计算机网络部分

- 1.五层 & 七层 网络模型 & 每层都有哪些协议
- 2.Http是什么
- 3.TCP三次握手与四次挥手，为啥是三次或者四次？
- 4.Https是什么 & 证书作用 & 可否自定义证书
- 5.浏览器访问一个url的过程？
- 6.Http 1.0 & 1.1 & 2.0 区别
- 7.什么是Socket?http是基于Socket实现的吗？
- 8.Token是什么？
- 9.Http缓存策略？
- 10.WebSocket是什么？和Socket的区别？

## Linux系统部分
## 架构部分
## gradle部分
## Kotlin部分
## ndk编程部分
## Flutter部分
## App优化专题
## 高级UI
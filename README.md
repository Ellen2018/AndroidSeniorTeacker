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
- 8.Android实现动画的原理[帧动画 & 补简动画 & 属性动画] & 矢量动画SVG & 矢量动画框架Lottie
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
- 14.JVM GC回收机制与Java 4种引用

## 数据结构与算法部分

- 1.空间复杂度 & 时间复杂度
- 2.数组 & 动态数组
- 3.单链表 & 双向链表 & 循环链表
- 4.栈
- 5.队列
- 6.树 & 遍历 & 完全二叉树 & 平衡二叉树
- 7.排序算法:冒泡 & 选择 & 插入 & 快排
- 8.查找算法:二分查找 & 跳表
- 9.其他算法:LeetCode刷题[链表反转，判断链表是否有环，栈模拟队列，队列模拟栈,找到单链表第k个结点等]

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

- 1.App应用开发架构:MV系列架构
- 2.Java设计模式
- 3.Kotlin设计模式
- 4.造轮子技术:Java反射，泛型，注解，APT,AOP,动态代理
- 5.复用思维:池化 & 多级缓存

## gradle部分

- Task生命周期
- 自定义Task
- 用gradle完成多渠道打包
- gradle

## Kotlin部分

- 1.Kotlin与Java为什么可以互调？存在那些坑？
- 2.Kotlin协程编程 & 协程原理
- 3.Kotlin泛型
- 4.Kotlin扩展方法
- 5.Kotlin自定义操作符
- 6.函数式编程  
- 7.Kotlin语法糖的原理:编译期
- 8.为什么Kotlin能有Java做不了的语法？

## ndk编程部分

- 1.C/C++基础学习
- 2.指针的理解
- 3.什么是cmake?
- 4.什么是JNI?什么是NDK?
- 5.native方法是什么？
- 6.native方法的命名，传参都有什么作用？
- 7.用JNI的方式对Java int类型数组排序然后返回。
- 8.so库是什么东西？
- 9.CPU架构又是什么东西？
- 10.ffmpeg & opencv & opengl学习[目前笔者对这些没有任何经验]

## Flutter部分
## App优化专题

- 1.内存泄漏 & 内存抖动 & 内存溢出
- 2.JVM GC回收机制 & 四种引用关系
- 3.内存泄漏的原因？
- 4.JVM内存结构中哪些区域存在OOM?
- 5.内存抖动是什么？会影响UI线程的流畅性吗？
- 6.UI卡顿的原理 & 卡顿的线上和线下检测
- 7.ANR的原理 & 线下线上如何监控ANR & 日志如何获取分析？
- 8.UI适配方案:老方案[不同分辨率采用不同的资源,配置不同的dp消除差异性] & 王道方案[今日头条适配方案]
- 9.冷启动优化，时间的统计 & 流程 & 优化
- 10.WebView 内存泄漏原因 & 加载缓慢如何优化？
- 11.Apk体积优化:Apk里都包含有什么 & 优化体积
- 12.布局优化，如何减少嵌套层级
- 13.线程优化:复用线程资源[线程池] & 及时停止无用线程资源 & 用工具分析App线程状态 & 尽量缩减线程数完成业务需求
- 14.内存使用优化:复用资源[池化] & 采用合适的数据结构，做到吞吐量合适

## 高级UI

- 1.理解原生控件的原理:LinearLayout & TextView,控件的背景是通过bitmap完成的吗？
- 2.Android的View绘制是在什么时候触发的？onCreate方法吗？此后的UI更新都是怎么样更新的？
- 3.UI绘制的详细的三个流程 & 事件分发过程
- 4.RecyclerView的缓存原理，借此打造可复用的表格控件 & 流式布局
- 5.setContentView是负责View绘制吗？
- 6.LayoutInflater它解析过程？围绕它如何拦截布局解析过程？
- 7.View的遍历，计算层级，打造一个布局优化的监控框架
- 8.自定义View之自定义属性
- 9.自定义控件有几种方式？
- 10.自定义控件时注意内存泄漏 & 内存抖动问题。
- 11.Vsync信号与UI绘制的三个方法onMeasure,onLayout,onDraw的联系
- 12.请求重新绘制的方法有哪些？区别是什么？
- 13.View和Activity & Window的关系
- 14.Fragment算是Activity里View的一员吗？
- 15.Toast & 对话框 & PopWindow & DialogFragment都会创建Window然后再放View？

## Android通信篇

- 1.对象和对象之间的通信方式:直接通信[方法调用] & 间接通信[内存回调通信 & 文件 & 其他等等] 
- 2.1v1,1vN,Nv1,NVN方式通信
- 3.线程间通信:共享资源 & 发送信号 & 线程安全问题
- 4.封装一个类似EventBus的框架
- 5.进程间通信方式:管道 & 信号量 & 文件 & Socket & 共享内存 & Binder等等
- 6.Binder & 腾讯MMKV跨进程通信高效率 实现原理:MMAP
- 7.Android中为什么Zygote采用Socket通信？
- 8.Android中除去Zygote之外的进程间通信为什么采用Binder?
- 9.Activity传输数据到另外一个Activity为什么采用Intent而不是HashMap?   
- 10.系统广播和本地广播的原理，为什么使用EventBus会更加合适App的开发
- 11.跨语言通信:JNI & WebView H5交互，它们的通信采用的什么原理？
  
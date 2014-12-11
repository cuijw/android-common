android common
===
some utils, common calsses, base workers.

LiteCommon项目简介
---
LiteCommon是一系列通用类、辅助类、工具类的集合，有以下特点：

- **1. 通用性强**：只有常用，才可入席。
- **2. 体积超小**：不到50K！加入增强IO包混淆后70K！
- **3. 纯  纯  纯**：类间独立，单挑大梁，极少耦合，就是单纯！

其中包括shell命令，静默安装，bitmap处理，文件操作，加密存储器，计数器，均值器，吐司，日志，校验，提示，网络监测等基础功能，以及一些Base64、MD5、Hex、Byte、Number、Dialog、Filed、Class、Package、Telephone、Random等工具类。

1. async包：异步与并发
-----
- **AsyncExecutor**：   一个简单的可以自定义线程池并发执行器
2. log包：日志
-----
- **Log**：             一个和android系统日志类同名(方便快速替换)的Log工具类，不同的是这个Log具有一键开关功能，方便快速开发打开调试模式。
3. assit包：辅助
-----
- **Averager**：        均值器， 添加一些列数字或时间戳，获取其均值。
- **Base64**：          Base64， 兼容到android1.0版本的Base64编解码器。
- **Check**：           检测类， 检测各种对象是否为null或empty。
- **LogReader**：       日志捕获器， 将某个程序、级别的日志记录到sd卡中，方便远程调试。
- **Network**：         网络探测器， 判断网络是否打开、连接、可用，以及当前网络状态。
- **SilentInstaller**： 安装器， 静默安装、卸载（仅在root过的手机上）。
- **TimeAverager**：    计时均值器， 统计耗时的同时，多次调用可得出其花费时间均值。
- **TimeCounter**：     计时器， 顾名思义，统计耗时用的。
- **Toastor**：         吐司， 解决多次连续弹出提示问题，可只弹出最后一次，也可连续弹出轻量级提示。
4. data包：数据处理
-----
- **DataKeeper**：       加密存储器，持久化工具，可加密，更简单、安全的存储（持久化）、获取数字、布尔值、甚至对象。
- **chipher包**：        放置加解密辅助类。
5. io包：文件与IO
-----
- **Charsets**：         字节编码类
- **FilenameUtils**：    通用的文件名字、路径操作工具类
- **FileUtils**：        通用文件操作工具类
- **IOUtils**：          通用IO流操作工具类
- **StringCodingUtils**：字符串编码工具类
- **stream包**：         IO流操作辅助类
6. utils包：常用工具类
-----
- **AndroidUtil**：     android信息， 获取android手机品牌、商家、版本号等信息
- **AppUtil**：         app工具， 检测是否前台运行，服务是否运行中等
- **BitmapUtil**：      位图操作， 拍照，裁剪，圆角，byte、string互转，压缩，放缩，保存等
- **ByteUtil**：        byte工具类
- **ClassUtil**：       类工具， 新建实例，判断类的类型等
- **DialogUtil**：      对话框工具类， 统一全局对话框
- **FieldUtil**：       属性工具类，获取属性值、获取属性泛型类型等
- **FileUtil**：        文件工具类
- **HexUtil**：         16进制工具类，16进制和byte、char像话转化
- **MD5Util**：         MD5工具类
- **NotificationUtil**：通知工具类，便捷显示到顶部栏
- **NumberUtil**：      数字工具类，各种数字安全转化
- **PackageUtil**：     应用程序类，打开、安装，卸载，启动应用以及获取应用信息
- **RandomUtil**：      随机工具类，产生随机string或数字，随机洗牌等
- **SerializeUtil**：   序列化工具类
- **ShellUtil**：       shell 命令工具类
- **TelephoneUtil**：   电话工具类，手机号、运营商、IMEI、IMSI等信息
- **VibrateUtil**：     震动工具类，调用系统震动功能


点击加入QQ群: [47357508](http://jq.qq.com/?_wv=1027&k=Z7l0Av)
-----
我的开源站点 ：[http://litesuits.com](http://litesuits.com/)
-----
我的博客站点 ：[http://vmatianyu.cn](http://vmatianyu.cn/)
-----

我的论坛帖子
-----
[LiteHttp：极简且智能的 android HTTP 框架库 (专注于网络)](http://www.eoeandroid.com/thread-326584-1-1.html)

[LiteOrm：极简且智能的 android ORM 框架库 (专注数据库)](url=http://www.eoeandroid.com/thread-538203-1-1.html)

[LiteAsync：强势的 android 异步 框架库 (专注异步与并发)](url=http://www.eoeandroid.com/thread-538212-1-1.html)

[LiteCommon：丰富通用的android工具类库(专注于基础组件)](url=http://www.eoeandroid.com/thread-538212-1-1.html)

我的博客帖子
-----
[关于java的线程并发和锁的总结](url=http://www.vmatianyu.cn/summary-of-the-java-thread-concurrency-and-locking.html)

[android开发技术经验总结60条](url=http://www.vmatianyu.cn/summarization-of-technical-experience.html)

[聚划算android客户端1期教训总结](url=http://www.vmatianyu.cn/poly-effective-client-1-issues-lessons.html)

[移动互联网产品设计小结](url=http://www.vmatianyu.cn/summary-of-mobile-internet-product-design.html)

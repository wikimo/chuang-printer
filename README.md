聊聊自研打单系统那些事

对电商业务来说，订单打单是一个绕不开的环节，成熟的电商平台都配备了完善的打单系统软件。对于中小平台或自建系统来说，订单打单就变得比较困难。

比较原始的方式通过电商平台导出订单，在对应的物流系统内发货后，再把物流运单号导回电商平台，这种方式单量少的情况下还好使，单量一多就容易数据混乱，还会涉及订单状态变化，让人崩溃。

高级一点会使用成熟的电商打单软件或者ERP/WMS系统，一般会自带打单功能，不过这类软件大部分功能齐全，第一次使用的时候估计一脸懵，需要一段时间摸索学习才行。另外，对商家来所还涉及使用成本，小商家可能不愿意花这钱。

还有一些情况，对于一些自研电商平台来说，同样需要具备打单能力，打单后的物流单号等数据需要实时回传，对于不同的ERP/WMS平台需要逐个去对接，成本不小。

如果在业务复杂度中等的情况下，单量数据在几百到上千单每天，产品SKU不多，这时如果有一款开源的打单系统可以快速接入原系统，且能灵活地做调整，是一种不错的选择。

市面上成熟的打单服务也比较多，如快递100、快递鸟、风火递等，同时他们也提供了各种数据接口，通过这些服务，我们可以相对快速的构建一套自己的打单系统。在经过一系列调研后，我们最终选择了基于快递100自研打单，打印插件基于Lodop。

我们自研的打单系统功能上相对比较简单，但也有每月几万单的数据，虽然小问题也比较多，但已经稳定跑了2年了。我们的打单系统主要解决了以下几个问题：
- 在线生成快递单号，无需手动导单；
- 一笔订单可同步多笔物流运单
- 支持系统对接、业务扩展，如停发通知等；


如果你也对打单系统感兴趣，欢迎交流沟通！
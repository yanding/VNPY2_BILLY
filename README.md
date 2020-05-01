# VNPY2_BILLY
之前VNPY 1版本中，我的个人代码很多是直接在VNPY库代码直接修改或者增加的。每次VNPY升级就是非常头疼，要做代码对比，在一些可能被更新覆盖的地方再次维护测试。而且因为更新的地方很乱，造成后面生产版本一致停留在VNPY1.92。    还是要慢慢迁移到VNPY2版本，毕竟很多吸引的特性。这次准备不在VNPY的库文件代码上修改，而是像引用NUMPY或者Pandas这样，采用引用继承的方式，把自己的代码和VNPY的库代码隔离；这样即使VNPY升级，个人代码不用太担心，只要简单测试，保证继承引用VNPY的类或方法正常工作就可以了。

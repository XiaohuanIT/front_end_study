组件是可以复用的Vue实例，且带有一个名字。可以在一个通过new Vue创建的Vue根实例中，将这个组件作为自定义元素来使用。

当一个组件被定义，data必须声明为返回一个初始数据对象的函数，因为组件可能被用来创建多个实例。如果data仍然是一个存粹的对象，则所有的实例将共享引用同一个数据对象！通过提供data函数，每次创建一个新实例后，我们能够调用data函数，从而返回初始数据的一个全新副本数据对象。



参考：

https://blog.csdn.net/xdnloveme/article/details/78035065

https://blog.csdn.net/weixin_41796631/article/details/82929139




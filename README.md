##一个展示 RecyclerView 下拉刷新和上拉加载更多的 Demo

完全使用原生控件实现非侵入式的下拉刷新和加载更多。

同时也是自己练习 RxJava 的小例子。

使用[HeaderViewRecyclerAdapter](https://gist.github.com/darnmason/7bbf8beae24fe7296c8a)完成了加载更多的进度展示。

Usage:

Step 1. Add the JitPack repository to your build file
Add it in your build.gradle at the end of repositories:

```
repositories {
    // ...
    maven { url "https://jitpack.io" }
}
```

Step 2. Add the dependency in the form

```Java
dependencies {
	 compile 'com.github.liangzhitao:SwipeRefreshRecyclerView:1.0'
}
```

运行效果如下图：
![](https://github.com/liangzhitao/SwipeRefreshRecyclerView/blob/master/RefreshRecyclerView.gif)

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
	 compile 'com.github.liangzhitao:SwipeRefreshRecyclerView:1.1'
}
```

运行效果如下图：
![](https://github.com/liangzhitao/SwipeRefreshRecyclerView/blob/master/RefreshRecyclerView.gif)

##License

```
The MIT License (MIT)

Copyright (c) 2015 liangzhitao

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

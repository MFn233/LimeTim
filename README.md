# 为啥会有这玩意
起初是因为想看现在时间是多少秒，现代手机电脑啥的都不显示当前秒数，于是就学网上随意做了一个。

```html
<div id="time"></div>
<script>setInterval("document.getElementById('time').innerHTML=new Date().toLocaleString();", 1000);</script>
<!-- 大概是这个样子 -->
```

后来心想，既然写了，那就稍微整好看点儿，写点css。

当时css也不咋会，甚至从头开始学了css，写了界面

再后来，觉得这个全屏放，如果没有搜索框是不是不太方便，于是做了个搜索框:

![image](https://github.com/MFn233/LimeTim/assets/103323756/50e3d709-e9a3-4226-bd1d-698de57c3317)

这个搜索框还是js实现的，为了搞懂原理我甚至从头还学了一下js基础

(~~这个网页跃迁还是因为我不知道怎么判断url长什么样才多加了一个框~~)

后来我寻思，既然都有搜索框了，放点我日常想用的东西，一点不就打开了吗

于是它出现了：

![image](https://github.com/MFn233/LimeTim/assets/103323756/8c1e642b-2f3f-465b-a44b-95ddd2492494)

我想现在你应该明白了。这玩意简直是我h5三巨头启蒙项目，我不得不传上来告诉大家，我自学html，都是因为我想做个时钟。

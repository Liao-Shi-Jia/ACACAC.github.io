# CSP-S2020 T1 儒略日
## [洛谷传送门](https://www.luogu.com.cn/problem/P7075)
___
###正解:
首先分析题目：
<br> 1. 得到 __常量__：
<br>① 格里高利历 ___400___ 年的天数 ___146097___
　　方法如下
 ```c++
int n, ans = 0;
scanf("%d", &n);
ans += (n / 4) * 366;
ans += (n - (n / 4)) * 365;
  ```
<br>② 儒略历 __4__ 年的天数 ___1461___　~~手算即可~~
<br>
<br>include

#CSP-S2020 T2 动物园
### [洛谷传送门](https://www.luogu.com.cn/problem/P7076)
___
####



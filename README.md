# CountdownDemo
两种方式实现倒计时

在做些活动界面或者限时验证码时, 经常会使用一些倒计时突出展现.

![倒计时.png](https://github.com/ZLFighting/ZLCountdownDemo/blob/master/CountdownDemo/截图.png)

> 现提供两种方案:
一.使用NSTimer定时器来倒计时
二.使用GCD来倒计时(用GCD这个写有一个好处，跳页不会清零, 跳页清零会出现倒计时错误的)

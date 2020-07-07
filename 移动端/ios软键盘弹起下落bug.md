# ios软键盘弹起下落bug

问题描述：

Hybird App ios软键盘弹起，输入完成后，软键盘下落，但页面还是被软键盘顶起时的样子，没有恢复无软键盘时的状态。

解决方法：

if(navigator.userAgent.match(/\(i[^;]+;( U;)? CPU.+Mac OS X/)) {
  document.addEventListener('focusout', function() {
    document.body.scrollTop = 0;
  });
}
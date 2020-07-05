# 设备像素比 (devicePixelRatio)

  > window.devicePixelRatio 是设备上物理像素和设备独立像素(device-independent pixels (dips))的比例

    window.devicePixelRatio = 物理像素 / dips

  物理像素也叫设备像素，是指显示器的真实像素，每个像素的大小是屏幕固有的属性，在出厂时就固定了

  设备独立像素也叫逻辑像素，是操作系统定义的一种像素单位

  CSS 像素，CSS 中的长度单位，在 CSS 中使用的 px 都是指 CSS 像素

  CSS 像素与独立像素的关系：

    缩放的比例就是 CSS 像素边长 / 设备独立像素边长

    在缩放比例是100%的情况下，一个 CSS 像素大小等于一个设备独立像素边长

  参考：

  [移动web开发之像素和DPR详解](https://blog.csdn.net/a419419/article/details/79295799)

  [设备像素比devicePixelRatio简单介绍](https://www.zhangxinxu.com/wordpress/2012/08/window-devicepixelratio/)

  [响应式设计——理解设备像素、设备独立像素和css像素](https://www.jianshu.com/p/6b1f94bfa263)

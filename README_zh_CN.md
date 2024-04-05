## 💌 缘起

一直都很馋wolai的动态日历图标，苦于思源笔记没有相关挂件，于是在GPT的帮助下，我开发了一个倒数日挂件

由于前端基础很薄弱，对思源笔记的API调用也不熟悉，到处拼贴竟然成功了哈哈哈，还是很佩服自己的。

## ✨界面预览

![17123430204421712343019600.png](https://fastly.jsdelivr.net/gh/Achuan-2/PicBed@pic/assets/17123430204421712343019600.png)

## 🐯主要功能

* 支持指定日期，动态进行倒数和正数日计算，依赖js代码，不依赖网络，支持添加具体事件名称

  * 如果指定日期早于当天日期，则正数
  * 如果指定日期晚于当天日期，则倒数
* 支持设置背景色，进行一定美化
* 配置支持自动保存到思源笔记的块属性，永久保留在笔记里
* 支持导出模板后加载配置，方便重复调用特定倒数日/正数日

## 🐛已知问题

* 设计的文字比较大，挂件块不适合调得太小
* 设置颜色Color Picker不支持粘贴颜色
* 为了保证初次加载挂件和模板能正常保存和读取块属性，加了500ms的延迟，所以显示会比较慢些

> 如果知道以上问题如何解决的大佬欢迎告知，感激不尽

## ❤ 致谢

* ChatGPT和Google Gemini：主体代码的编写
* [Zuoqiu-Yingyi/widget-query](https://github.com/Zuoqiu-Yingyi/widget-query)：学习挂件加载设置默认宽度和高度
* [OpaqueGlass/progressBarT-sywidget](https://github.com/OpaqueGlass/progressBarT-sywidget)：学习挂件如何保存和读取配置。

## ☎️意见交流

欢迎在[Github](https://github.com/Achuan-2/siyuan-themes-tsundoku)提issue或是通过邮箱联系我
---
wiki: xtc-root
title: 4点线机型
author: Mengmiya1027
references:
  - '[ATB图文教程 by Josephヽ( ^ω^ ゞ )-Z8SNB（应该是这入吧……](https://qm.qq.com/q/Y1Ix4uSE0K)'
---

{% note color:yellow 注意 本节仅适用于4点线机型手表。6点线机型手表，请查看[下一节](/wiki/xtc-flash/six-point/) %}

###### 请确认：
{% checkbox checked:true 依据<a href="/wiki/xtc-flash/preparation/">准备工作</a>，我的手表是4点线机型 %}

{% quot 连接手表 el:h2 %}

完成上一步后，软件会开始搜索手表，这时我们需要短接。

这是{% emp 非常重要 %}的一步，直接决定您的手表是否能顺利连接上电脑。

{% note color:red 警告 若操作不当则可能导致手表短路损坏！请严格按照教程执行。 %}

{% image /public/images/xtc/root/four-connecting.jpg 四点线机型短接示意 %}

{% timeline %}
<!-- node 第 1 步 · 接线关机 -->
请拿出事先购买的数据线，将手表通过数据线接入电脑。四点线接在充电口位置，接上线后将手表关机。
<!-- node 第 2 步 · 短接 -->
然后左手按住手表电源键，右手持续用金属镊子/平头螺丝刀按在SIM卡槽内两个铜色金属点上。
<!-- node 第 3 步 · 等待连接 -->
待软件显示 {% mark ADB设备已连接！ color:green %}，此时便可以松手。
{% endtimeline %}

{% note color:yellow 提示 请将手表放置在宽敞、无杂物、不易误触的桌面上，以防无意触碰导致连接断开 %}

下一步请查看[正式刷写](/wiki/xtc-flash/rooting/)

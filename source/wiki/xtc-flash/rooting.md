---
wiki: xtc-root
title: 正式刷写
author: Mengmiya1027
references:
  - '[ATB图文教程 by Josephヽ( ^ω^ ゞ )-Z8SNB（应该是这入吧……](https://qm.qq.com/q/Y1Ix4uSE0K)'
---

## 概览

{% timeline %}
<!-- node 相册备份 -->
按需备份相册（输入 {% kbd y %}/{% kbd n %}）。
<!-- node 全自动轮椅模式 -->
工具自动处理 boot、recovery，静候即可。
<!-- node 应用安装 -->
安装预装应用、恢复相册、预装优化。
<!-- node 完成 -->
出现 ROOT 完毕提示，大功告成。
{% endtimeline %}

{% quot 相册备份 el:h2 %}

完成前面的步骤后，ATB将会询问您是否要备份相册，这个根据各位的需求决定。

如果没有备份可以输入{% kbd y %}并按下{% kbd Enter↩︎ %}键。如果已经备份好了，或者不需要备份，请输入{% kbd n %}并按下{% kbd Enter↩︎ %}以跳过备份。

{% quot 全自动轮椅模式 el:h2 %}

相册备份完后，工具会让您的手表进入9008模式，然后会向手表发送引导、处理boot、刷入recovery，进入fastboot等。

这一过程中的操作由电脑自动完成，您只需要在电脑前等待即可。

{% image /public/images/xtc/root/progress1.png 全自动轮椅模式执行中 %}

{% note color:red 警告 在手表已经稳定连接至电脑，且数据线不易脱落的情况下，请勿触碰您的手表。<br>
在root过程完成前请勿将手表连接至网络。<br>
若过程中手表弹出绑定号，请勿进行绑定，否则将会导致“验证异常”！ %}

{% quot 应用安装、相册恢复、预装优化 el:h2 %}

接下来会自动进入安装应用的环节。

“预装应用”(共7个)建议尽量安装，不输入`no`。

然后工具箱会询问您是否要恢复相册，这里根据个人需求选择，按{% kbd n %}选择否，或者按{% kbd y %}选择是。

随后是预装优化部分。该部分会为您安装一些实用的模块与应用，推荐安装。

{% image /public/images/xtc/root/progress2.png 应用安装与相册恢复环节 %}

此后，ATB将会询问是否安装禁用模式切换的桌面。

“禁用模式切换的桌面”就是不会有长续航模式、上课/睡眠禁用模式等的切换，在家长端App设置该模式后手表仍然可以运行已安装的App。

{% note color:yellow 警告 不建议安装“禁用模式切换的桌面”。
<br>手表在root过程中，会出现不同程度的发热情况，可能触发高温禁用。
<br>安装禁用模式切换的桌面，可能导致永久锁定在高温禁用。解决办法为重装桌面。
<br>如果您实在需要禁用模式切换，建议稍后在`SystemPlus`软件中修改。%}

{% image /public/images/xtc/root/progress3.png 预装优化环节 %}

{% note color:red
ATB可能会询问是否要刷入“原生修复”和“破解SystemPlus和WeiChatPro2”模块，此时请拒绝，否则可能导致手表无法使用！<br><br>若ATB没有询问相关事宜，请跳过本提示。
%}

{% image /public/images/xtc/root/progress4.png 接近完成，等待最终提示 %}

继续等待直到ATB出现如下提示：

```bash
是否进行预装优化[包括模块和应用，期间需多次选择]？
1.是
2.否
```

或者

```bash
- 跨越山海 终见曙光 -
您的手表已ROOT完毕，耗时：.......
```

至此，您的手表也就{% mark 成功获取root权限 color:green %}了，可以任意安装第三方应用（微信、QQ、视频、游戏等），刷入Magisk模块，以及解除充电禁用、解除录像30秒限制、屏蔽上课禁用、屏蔽小天才官方的系统更新等等。{% emoji tieba huaji %}
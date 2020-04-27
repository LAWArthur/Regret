﻿# Regret
version a1.4.0

[发布包](https://gitee.com/LAWArthur/Regret/releases/)

Alpha R1 的所有开发任务均已完成！【撒花】

## 简介
重置了剧情系统，增加了NPC的游走&攻击动作。

TOFIX: 交互系统尚未完善，以此带来的BUG将会被修复，敬请谅解

UPNEXT: Alpha R2将会重制交互系统，添加场景更换等。

### 物品简介
#### 祈念
祈念，坊间流传为“阿片”（感谢lwy提供名字【鞠躬】）之物，乃人类愿望的形式化表现。
祈念可以在一定条件下被刻录在水晶片、金属片等载体上，会在野外有人烟处自然形成，人类也有技术对普通祈念进行锻造。

#### 然后就没了

## 操作指南

### 移动
`WASD`，emmm不多说了吧

`Shift`键冲刺

### 视角
通过鼠标移动控制视角以及人物朝向。

`` ` ``键（反撇，`~`)可以将视角与人物朝向脱离。

> Note：在攻击时人物朝向处于不可控制状态（由攻击动作控制）

### 交互
当视角朝向一个可交互对象（物品、NPC、etc.)时，在十字标旁会出现该对象的名称。此时按下`E`键可以进行交互。

#### 物品
交互对象为物品时，若该物品处于未拾取状态，将会拾取进入背包。

#### 商店NPC
交互对象为商店NPC时，交互将会打开商店。（测试场景中的NPC就是商店NPC）

### 背包
按`Tab`键可以打开背包。通过鼠标点击物品栏并按背包视图右下角的`Drop` `Equip`可以丢弃/装备物品到手中。

你也可以使用键盘上下左右四个箭头在背包中导航，并使用`Q`键丢弃，`E`键装备。

### 攻击

长按鼠标左键可以进行攻击。

徒手攻击不会造成任何伤害（我会改的，会改的），使用武器攻击将通过一定公式对对方造成伤害。

在攻击过程（按下鼠标左键过程）中每一次触及对方视为一次伤害。这也是说，伤害次数很大程度上取决于攻击动作。

攻击后，武器自带效果将会被附加到目标身上。

#### 攻击动作
攻击动作可在右下角看到。通过按下`6 7 8 9 0`五个键可以切换攻击动作（你问我为什么不是12345？12345要留给装备快捷栏【虽然可能永远都不会有】）。本测试版内置三种攻击动作。

> Note：如果手持物品有专属攻击动作，则该物品的动作会覆盖原攻击动作。

#### 攻击效果
每一次伤害都会附加一个攻击效果（如中毒、流血等）。


[issues](https://github.com/LAWArthur/Regret/issues/)求虐求吐槽

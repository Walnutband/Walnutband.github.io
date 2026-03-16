---
layout: single
author_profile: true
---
大多系统开发的尝试都基本中道崩殂，导致这个项目好像成了一大坨Shit。

动画系统和行为树编辑器勉强能用，一些基于UGUI扩展的组件功能合格，但还只是UI层面的功能，没有经过逻辑层的测试，而且还没有一个像样的UI系统来管理游戏运行时的UI。

本来尝试开发的技能系统参考虚幻引擎的GAS，AbilitySystemComponent、AttributeSet、GameplayEffect的逻辑大概能用，不过到了AbilityTask，没有成熟的编辑器或者说技能编辑器，导致技能的表现层和一些区间逻辑（比如连段区间）非常难以编辑，而且现在写的AbilityTaskEditor也还不支持循环执行，不好做蓄力攻击之类的行为。而之前对于技能编辑器开发的尝试，只弄出来了一个刻度尺，虽然UI交互效果不错，不过没有后续了，现在看来，至少得先把技能系统搞清楚再说。


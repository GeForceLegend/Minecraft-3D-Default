---
name: Bug report
about: Create a report to help me fix it
title: ''
labels: ''
assignees: ''

---

**These are informations that help me catch the bug better. You can delete it before you submit a bug report.**
**这是为了方便我更好的查找bug的信息。你可以在你提交bug汇报之前删除这些信息。**

1. Make sure this bug is caused by the resource pack it self, but not mods or other resource packs. I will not work on compatibility with these resources.
请确保这个bug是由资源包本身，而不是mod或者其他资源包引起的。我不会考虑做mod或者其他资源包的兼容工作。

2. If you are experiencing any bug related to items, including crash while rendering something, try deleteing `assets/minecraft/models/item/generated.json`. Its my hacky way to fix [MC-73186](https://bugs.mojang.com/browse/MC-73186).
如果你碰到了任何与物品相关的问题，包括渲染特定物品时崩溃，尝试删除`assets/minecraft/models/item/generated.json`。这是我为了修复 [MC-73186](https://bugs.mojang.com/browse/MC-73186) 采取的极端方法。

3. A latest.log (in `.minecraft/logs`), crash report (in `.minecraft/crash-reports`) or even hs_err_pid(logID).log (in `.minecraft`) if exists and its create time matches crashing will helps a lot. Provide them if you can.
latest.log（位于`.minecraft/logs`），以及如果出现了并且时间对的上崩溃，崩溃报告（位于`.minecraft/crash-reports`）和 hs_err_pid(logID).log （位于`.minecraft`）能提供非常多的帮助，如果能的话请提供它们。

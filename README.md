<p align="center">
    <img width="100" src="https://user-images.githubusercontent.com/35565811/147811357-20cbb197-8080-483c-9bbb-9bfddf6d8a3e.png">
</p>
<h2 align="center">Git Flow Learn</h2>

> 用于学习测试开发流程, 可以直接尝试或 fork 后尝试。

#### Git 工作流程：
最大原则是"上游优先"（upsteam first），即只存在一个主分支`main`，它是所有其他分支的"上游"。只有上游分支采纳的代码变化，才能应用到其他分支。长期分支只保留`main`和`release`，其他分支用完即删。
+ `main` 主干分支 （保护分支）
+ `release/**` 发布分支 （保护分支)
+ `bugfix/**` 修复bug分支 (用完即删)
+ `feature/**` 特性分支 (多人合作完成某一特性时用，用完即删)
+ `personal/username/**` 个人分支 (用完即删)


<div align=center>
    <img width="750" src="https://user-images.githubusercontent.com/35565811/146736286-ee5bf967-7fd7-428b-83f4-0cd486faf7b0.png">
</div>


<h1 align="center"></h1>

#### 测试commit区：
```
commit 1
commit 2
commit 3
commit 4
commit 5
commit 6
commit 7
commit 8
commit x
```

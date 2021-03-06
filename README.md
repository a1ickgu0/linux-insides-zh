Linux 内核揭密
==============

[![Join the chat at https://gitter.im/MintCN/linux-insides-zh](https://badges.gitter.im/MintCN/linux-insides-zh.svg)](https://gitter.im/MintCN/linux-insides-zh?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

一系列关于 Linux 内核和其内在机理的帖子。

**目的很简单** - 分享我对 Linux 内核内在机理的一点知识，帮助对 Linux 内核内在机理感兴趣的人，和其他低级话题。

**问题/建议**: 通过在 twitter 上 [@0xAX](https://twitter.com/0xAX) ，直接添加 [issue](https://github.com/0xAX/linux-insides/issues/new) 或者直接给我发[邮件](mailto:anotherworldofworld@gmail.com),请自由地向我提出任何问题或者建议。

##翻译进度

| 章节|译者|翻译进度|
| ------------- |:-------------:| -----:|
| 1. [Booting](https://github.com/MintCN/linux-insides-zh/tree/master/Booting)||正在进行|
|├ [1.0](https://github.com/MintCN/linux-insides-zh/blob/master/Booting/README.md)|[@xinqiu](https://github.com/xinqiu)|已完成|
|├ [1.1](https://github.com/MintCN/linux-insides-zh/blob/master/Booting/linux-bootstrap-1.md)|[@hailincai](https://github.com/hailincai)|已完成|
|├ [1.2](https://github.com/MintCN/linux-insides-zh/blob/master/Booting/linux-bootstrap-2.md)|[@hailincai](https://github.com/hailincai)|已完成|
|├ [1.3](https://github.com/MintCN/linux-insides-zh/blob/master/Booting/linux-bootstrap-3.md)|[@hailincai](https://github.com/hailincai)|已完成|
|├ [1.4](https://github.com/MintCN/linux-insides-zh/blob/master/Booting/linux-bootstrap-4.md)|[@zmj1316](https://github.com/zmj1316)|已完成|
|└ [1.5](https://github.com/MintCN/linux-insides-zh/blob/master/Booting/linux-bootstrap-5.md)|[@chengong](https://github.com/chengong)|正在进行|
| 2. [Initialization](https://github.com/MintCN/linux-insides-zh/tree/master/Initialization)||正在进行|
|├ [2.0](https://github.com/MintCN/linux-insides-zh/blob/master/Initialization/README.md)|[@mudongliang](https://github.com/mudongliang)|已完成|
|├ [2.1](https://github.com/MintCN/linux-insides-zh/blob/master/Initialization/linux-initialization-1.md)|[@dontpanic92](https://github.com/dontpanic92)|正在进行|
|├ [2.2](https://github.com/MintCN/linux-insides-zh/blob/master/Initialization/linux-initialization-2.md)|[@dontpanic92](https://github.com/dontpanic92)|正在进行|
|├ [2.3](https://github.com/MintCN/linux-insides-zh/blob/master/Initialization/linux-initialization-3.md)|[@dontpanic92](https://github.com/dontpanic92)|正在进行|
|├ [2.4](https://github.com/MintCN/linux-insides-zh/blob/master/Initialization/linux-initialization-4.md)|[@bjwrkj](https://github.com/bjwrkj)|已完成|
|├ [2.5](https://github.com/MintCN/linux-insides-zh/blob/master/Initialization/linux-initialization-5.md)|[@bjwrkj](https://github.com/bjwrkj)|正在进行|
|├ [2.6](https://github.com/MintCN/linux-insides-zh/blob/master/Initialization/linux-initialization-6.md)|[@bjwrkj](https://github.com/bjwrkj)|正在进行|
|├ [2.7](https://github.com/MintCN/linux-insides-zh/blob/master/Initialization/linux-initialization-7.md)|[@bjwrkj](https://github.com/bjwrkj)|正在进行|
|├ [2.8](https://github.com/MintCN/linux-insides-zh/blob/master/Initialization/linux-initialization-8.md)|[@bjwrkj](https://github.com/bjwrkj)|正在进行|
|├ [2.9](https://github.com/MintCN/linux-insides-zh/blob/master/Initialization/linux-initialization-9.md)|[@bjwrkj](https://github.com/bjwrkj)|正在进行|
|└ [2.10](https://github.com/MintCN/linux-insides-zh/blob/master/Initialization/linux-initialization-10.md)|[@bjwrkj](https://github.com/bjwrkj)|正在进行|
| 3. [Interrupts](https://github.com/MintCN/linux-insides-zh/tree/master/Interrupts)||正在进行|
|├ [3.0](https://github.com/MintCN/linux-insides-zh/blob/master/Interrupts/README.md)|[@littleneko](https://github.com/littleneko)|正在进行|
|├ [3.1](https://github.com/MintCN/linux-insides-zh/blob/master/Interrupts/interrupts-1.md)|[@littleneko](https://github.com/littleneko)|正在进行|
|├ [3.2](https://github.com/MintCN/linux-insides-zh/blob/master/Interrupts/interrupts-2.md)|[@cloudusers](https://github.com/cloudusers)|正在进行|
|├ [3.3](https://github.com/MintCN/linux-insides-zh/blob/master/Interrupts/interrupts-3.md)|[@cloudusers](https://github.com/cloudusers)|正在进行|
|├ [3.4](https://github.com/MintCN/linux-insides-zh/blob/master/Interrupts/interrupts-4.md)|[@cloudusers](https://github.com/cloudusers)|正在进行|
|├ [3.5](https://github.com/MintCN/linux-insides-zh/blob/master/Interrupts/interrupts-5.md)|[@cloudusers](https://github.com/cloudusers)|正在进行|
|├ [3.6](https://github.com/MintCN/linux-insides-zh/blob/master/Interrupts/interrupts-6.md)|[@cloudusers](https://github.com/cloudusers)|正在进行|
|├ [3.7](https://github.com/MintCN/linux-insides-zh/blob/master/Interrupts/interrupts-7.md)|[@cloudusers](https://github.com/cloudusers)|正在进行|
|├ [3.8](https://github.com/MintCN/linux-insides-zh/blob/master/Interrupts/interrupts-8.md)|[@cloudusers](https://github.com/cloudusers)|正在进行|
|├ [3.9](https://github.com/MintCN/linux-insides-zh/blob/master/Interrupts/interrupts-9.md)|[@zhangyangjing](https://github.com/zhangyangjing)|已完成|
|└ [3.10](https://github.com/MintCN/linux-insides-zh/blob/master/Interrupts/interrupts-10.md)|[@worldwar](https://github.com/worldwar)|已完成|
| 4. [System calls](https://github.com/MintCN/linux-insides-zh/tree/master/SysCall)||正在进行|
|├ [4.0](https://github.com/MintCN/linux-insides-zh/blob/master/SysCall/README.md)|[@mudongliang](https://github.com/mudongliang)|已完成|
|├ [4.1](https://github.com/MintCN/linux-insides-zh/blob/master/SysCall/syscall-1.md)|[@qianmoke](https://github.com/qianmoke)|已完成|
|├ [4.2](https://github.com/MintCN/linux-insides-zh/blob/master/SysCall/syscall-2.md)|[@qianmoke](https://github.com/qianmoke)|已完成|
|├ [4.3](https://github.com/MintCN/linux-insides-zh/blob/master/SysCall/syscall-3.md)|[@1a1a11a](https://github.com/1a1a11a)|正在进行|
|└ [4.4](https://github.com/MintCN/linux-insides-zh/blob/master/SysCall/syscall-4.md)|[@1a1a11a](https://github.com/1a1a11a)|正在进行|
| 5. [Timers and time management](https://github.com/MintCN/linux-insides-zh/tree/master/Timers)||正在进行|
|├ [5.0](https://github.com/MintCN/linux-insides-zh/blob/master/Timers/README.md)|[@mudongliang](https://github.com/mudongliang)|已完成|
|├ [5.1](https://github.com/MintCN/linux-insides-zh/blob/master/Timers/timers-1.md)|[@1a1a11a](https://github.com/1a1a11a)|正在进行|
|├ [5.2](https://github.com/MintCN/linux-insides-zh/blob/master/Timers/timers-2.md)|[@1a1a11a](https://github.com/1a1a11a)|正在进行|
|├ [5.3](https://github.com/MintCN/linux-insides-zh/blob/master/Timers/timers-3.md)|[@1a1a11a](https://github.com/1a1a11a)|正在进行|
|├ [5.4](https://github.com/MintCN/linux-insides-zh/blob/master/Timers/timers-4.md)|[@1a1a11a](https://github.com/1a1a11a)|正在进行|
|├ [5.5](https://github.com/MintCN/linux-insides-zh/blob/master/Timers/timers-5.md)|[@1a1a11a](https://github.com/1a1a11a)|正在进行|
|├ [5.6](https://github.com/MintCN/linux-insides-zh/blob/master/Timers/timers-6.md)|[@1a1a11a](https://github.com/1a1a11a)|正在进行|
|└ [5.7](https://github.com/MintCN/linux-insides-zh/blob/master/Timers/timers-7.md)|[@1a1a11a](https://github.com/1a1a11a)|正在进行|
| 6. [Synchronization primitives](https://github.com/MintCN/linux-insides-zh/tree/master/SyncPrim)||正在进行|
|├ [6.0](https://github.com/MintCN/linux-insides-zh/blob/master/SyncPrim/README.md)|[@mudongliang](https://github.com/mudongliang)|已完成|
|├ [6.1](https://github.com/MintCN/linux-insides-zh/blob/master/SyncPrim/sync-1.md)|[@keltoy](https://github.com/keltoy)|已完成|
|├ [6.2](https://github.com/MintCN/linux-insides-zh/blob/master/SyncPrim/sync-2.md)|[@keltoy](https://github.com/keltoy)|正在进行|
|├ [6.3](https://github.com/MintCN/linux-insides-zh/blob/master/SyncPrim/sync-3.md)|[@huxq](https://github.com/huxq)|已完成|
|├ [6.4](https://github.com/MintCN/linux-insides-zh/blob/master/SyncPrim/sync-4.md)|[@huxq](https://github.com/huxq)|正在进行|
|├ [6.5](https://github.com/MintCN/linux-insides-zh/blob/master/SyncPrim/sync-5.md)||未开始|
|└ [6.6](https://github.com/MintCN/linux-insides-zh/blob/master/SyncPrim/sync-6.md)||未开始|
| 7. [Memory management](https://github.com/MintCN/linux-insides-zh/tree/master/MM)||正在进行|
|├ [7.0](https://github.com/MintCN/linux-insides-zh/blob/master/MM/README.md)|[@mudongliang](https://github.com/mudongliang)|已完成|
|├ [7.1](https://github.com/MintCN/linux-insides-zh/blob/master/MM/linux-mm-1.md)|[@choleraehyq](https://github.com/choleraehyq)|已完成|
|├ [7.2](https://github.com/MintCN/linux-insides-zh/blob/master/MM/linux-mm-2.md)|[@choleraehyq](https://github.com/choleraehyq)|已完成|
|└ [7.3](https://github.com/MintCN/linux-insides-zh/blob/master/MM/linux-mm-3.md)||未开始|
| 8. SMP||上游未开始|
| 9. [Concepts](https://github.com/MintCN/linux-insides-zh/tree/master/Concepts)||正在进行|
|├ [9.0](https://github.com/MintCN/linux-insides-zh/blob/master/Concepts/README.md)|[@mudongliang](https://github.com/mudongliang)|已完成|
|├ [9.1](https://github.com/MintCN/linux-insides-zh/blob/master/Concepts/per-cpu.md)|[@up2wing](https://github.com/up2wing)|正在进行|
|├ [9.2](https://github.com/MintCN/linux-insides-zh/blob/master/Concepts/cpumask.md)|[@up2wing](https://github.com/up2wing)|正在进行|
|└ [9.3](https://github.com/MintCN/linux-insides-zh/blob/master/Concepts/initcall.md)|[@up2wing](https://github.com/up2wing)|正在进行|
| 10. [DataStructures](https://github.com/MintCN/linux-insides-zh/tree/master/DataStructures)||已完成|
|├ [10.0](https://github.com/MintCN/linux-insides-zh/blob/master/DataStructures/README.md)|[@mudongliang](https://github.com/mudongliang)|已完成|
|├ [10.1](https://github.com/MintCN/linux-insides-zh/blob/master/DataStructures/dlist.md)|[@oska874](http://github.com/oska874) [@mudongliang](https://github.com/mudongliang)|已完成|
|├ [10.2](https://github.com/MintCN/linux-insides-zh/blob/master/DataStructures/radix-tree.md)|[@a1ickgu0](https://github.com/a1ickgu0)|已完成|
|└ [10.3](https://github.com/MintCN/linux-insides-zh/blob/master/DataStructures/bitmap.md)|[@cposture](https://github.com/cposture)|已完成|
| 11. [Theory](https://github.com/MintCN/linux-insides-zh/tree/master/Theory)||正在进行|
|├ [11.0](https://github.com/MintCN/linux-insides-zh/blob/master/Theory/README.md)|[@mudongliang](https://github.com/mudongliang)|已完成|
|├ [11.1](https://github.com/MintCN/linux-insides-zh/blob/master/Theory/Paging.md)|[@mudongliang](https://github.com/mudongliang)|已完成|
|├ [11.2](https://github.com/MintCN/linux-insides-zh/blob/master/Theory/ELF.md)|[@mudongliang](https://github.com/mudongliang)|已完成|
|└ [11.3](https://github.com/MintCN/linux-insides-zh/blob/master/Theory/asm.md)||未开始|
| 12. Initial ram disk||上游未开始|
| 13. [Misc](https://github.com/MintCN/linux-insides-zh/tree/master/Misc)||正在进行|
|├ [13.0](https://github.com/MintCN/linux-insides-zh/blob/master/Misc/README.md)|[@mudongliang](https://github.com/mudongliang)|已完成|
|├ [13.1](https://github.com/MintCN/linux-insides-zh/blob/master/Misc/how_linux_compile.md)|[@oska874](https://github.com/oska874)|已完成|
|├ [13.2](https://github.com/MintCN/linux-insides-zh/blob/master/Misc/linkers.md)|[@zmj1316](https://github.com/zmj1316)|已完成|
|├ [13.3](https://github.com/MintCN/linux-insides-zh/blob/master/Misc/contribute.md)||正在进行|
|└ [13.4](https://github.com/MintCN/linux-insides-zh/blob/master/Misc/program_startup.md)|[@mudongliang](https://github.com/mudongliang)|已完成|
| 14. [KernelStructures](https://github.com/MintCN/linux-insides-zh/tree/master/KernelStructures)||正在进行|
|├ [14.0](https://github.com/MintCN/linux-insides-zh/tree/master/KernelStructures/README.md)|[@mudongliang](https://github.com/mudongliang)|已完成|
|└ [14.1](https://github.com/MintCN/linux-insides-zh/tree/master/KernelStructures/idt.md)||未开始|
##翻译认领规则

为了避免多个译者同时翻译相同章节的情况出现，请按照以下规则认领自己要翻译的章节：

* 在 [README.md](https://github.com/MintCN/linux-insides-zh/blob/master/README.md) 中查看你想翻译的章节的状态；
* 在确认想翻译的章节没有被翻译之后，开一个 issue ，告诉大家你想翻译哪一章节，同时提交申请翻译的 PR ，将 [README.md](https://github.com/MintCN/linux-insides-zh/blob/master/README.md) 中的翻译状态修改为“正在进行”；
* 首先，从上游的[英文库](https://github.com/0xAX/linux-insides)中得到该章节的最新版本，将修改提交到我们的中文库中；
* 然后翻译你认领的章节；
* 完成翻译之后，提交翻译内容的 PR ，待 PR 被 merge 之后，关闭 issue ；
* 最后，将 [README.md](https://github.com/MintCN/linux-insides-zh/blob/master/README.md) 中的翻译状态修改为“已完成”，同时不要忘记把自己添加到 [contributors.md](https://github.com/MintCN/linux-insides-zh/blob/master/contributors.md) 中。

翻译前建议看 [TRANSLATION_NOTES.md](https://github.com/MintCN/linux-insides-zh/blob/master/TRANSLATION_NOTES.md) 。关于翻译约定，大家有任何问题或建议也请开 issue 讨论。

##作者

[@0xAX](https://twitter.com/0xAX)

##中文维护者

[@xinqiu](https://github.com/xinqiu)

[@mudongliang](https://github.com/mudongliang)

##中文贡献者

详见 [contributors.md](https://github.com/MintCN/linux-insides-zh/blob/master/contributors.md)

##LICENSE

Licensed [BY-NC-SA Creative Commons](http://creativecommons.org/licenses/by-nc-sa/4.0/).



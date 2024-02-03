# Demon's Souls Remasterd Cheat Sheet

To view the cheat sheet [click here](http://iforgottosave.github.io/demons-souls-cheat-sheet/)

The foundation of this guide was based on [Dark Souls 3 Cheat Sheet](https://github.com/ZKjellberg/dark-souls-3-cheat-sheet) created by [Zachary Kjellberg](https://github.com/ZKjellberg/) and [Demon's Souls Cheat sheet](https://github.com/iforgottosave/demons-souls-cheat-sheet) created by [iforgottosave](https://github.com/iforgottosave).

Since this repo is forked from the original Demon's Souls Cheat Sheet and only updated from it, it comprises of the same setup, hence following the original authors' guide.
## Contribution Guide

If you are interested in contributing to this guide, submit an Issue Report or a Pull Request

For some background on how the guide code is written, here is a sample item on the checklist:

```
<li data-id="playthrough_9_1" class="f_stone f_misc">Head left until you can enter a room with a Renowned Hero's Soul and Shard of Sharpstone x2</li>
```

The **data-id** is a unique ID used to store the user's progress. For example, ***playthrough_9_1*** is the 1st task in zone 9. New data-ids must be used in ascending order, but you can place the new entries anywhere within a zone

The **class="f_stone f_misc"** field is used for the filtering system. This task provides the user with a Stone and a Consumable, so we use **f_stone** and **f_misc**. The full list of filter classes is:

| Class   | Description |
| ---     | --- |
| f_boss  | Bosses |
| f_npc   | NPCs |
| f_stone | Stones |
| f_soul  | Demon Souls |
| f_ring  | Rings |
| f_weap  | Weapons & Shields |
| f_arm   | Armors |
| f_misc  | *any other items* |

If none of these filter classes match, use **class="f_none"**

As NG+ does not add any new and/or differing items, there is no class for it

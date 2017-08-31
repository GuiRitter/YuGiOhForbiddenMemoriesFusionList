# YuGiOhForbiddenMemoriesFusionList

Yes. 722 cards, 521 284 possible combinations (assuming no commutativity, but it is commutative). I wrote an [AutoHotKey](https://autohotkey.com/) script and a program in [Java](https://en.wikipedia.org/wiki/Java_(programming_language)) with [JNA](https://github.com/java-native-access/jna#readme) that automatically plays the [game](https://en.wikipedia.org/wiki/List_of_Yu-Gi-Oh!_video_games#Yu-Gi-Oh.21_Forbidden_Memories) and checks every possible fusion, and write the results to text files. Unfortunately, I blindly updated JNA and the new version doesn't work as the old one, so my program is not working anymore. I'll make a new version and then upload it here. Until then, the list that was compiled can be kept here, so the results can still be used. I left the program running overnight everyday and it took about a month to check all fusions.

Consider that every fusion is in the form `X + Y = Z`. The fusion list is in the following format:

```
  X1
+ Y2
= Z3
+ Y3
= Z4
  ⋮
----
  X2
+ Y2
= Z5
----
  X9
----
  ⋮
```

As I wrongly knew, know that it is _not_ legal to own a [PlayStation](https://en.wikipedia.org/wiki/PlayStation_(console))'s [BIOS](https://en.wikipedia.org/wiki/BIOS), even if you do own a PlayStation. Fortunately, there's an emulator called [PCSX-Reloaded](https://en.wikipedia.org/wiki/PCSX-Reloaded) that doesn't need a BIOS, so it's perfectly legal to play emulated PlayStation games, as long as you own the games themselves. If the current build of PCSX-R doesn't work with Yu-Gi-Oh for some reason, use [this](http://pcsxr.codeplex.com/workitem/12066) build.

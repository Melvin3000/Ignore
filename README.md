Ignore
=====

A bukkit plugin that lets player's ignore each other.

Do note that this plugin due to technical reasons replaces the /me, /tell, /w and /msg commands. If another plugin also replaces any of these commands, it will conflict with this plugin.

Commands
-----
```
/ignore [player]
```
(Un)ignores [player] (it's toggled).
If no player is specified, shows who you are currently ignoring.

Compiling
-----
Just run `make` in the directory. To specify the bukkit jar and/or java version, run it as
```
make BUKKIT=/path/to/bukkit.jar JAVA=1.7
```

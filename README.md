# minecraft-structure-builder
A piece of code allowing you to almoust instantly build parametrical or implicit equations in java minecraft 1.13+
You can use presets or set your own equation. To make the thing work you should make a datapack in the minecraft world you want to build like this:
C:\\Users\\'user-name'\\AppData\\Roaming\\.minecraft\\saves\\'world-name'\\datapacks\\'datapack-name'\\data\\'namespace'\\functions\\'function-name'.mcfunction
To test if everything works you should edit the 'function-name.mcmeta' in a text editor and type in the following:"setblock ~ ~2 ~ minecraft:diamond_block"; go to
your minecraft world and type in chat "/function 'namespace':'function-name'". If everything works you should see a diamond block up your head.

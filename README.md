# ExtraDrops
A lightweight plugin that adds Rust-esque resource modification to Minecraft.
For documentation's sake earlier versions of the plugin have been added as well.

HOW TO USE:
Drag this into your plugins folder in your minecraft world file.

You must have op to use these commands! Also, if a block has two or more words as its tag, you must separate the two words with an underscore. For example, grass block is GRASS_BLOCK (lowercase entry works fine).
commands:
  setblockmult:
    description: Set a multiplier for a block type
    usage: /setblockmult <block> <amount>
    
  setblockmultbatch:
    description: Set a multiplier for multiple block types
    usage: /setblockmultbatch <block,amount;block,amount;...>
    
  setblockmultglobal:
    description: Set a universal multiplier for all block types
    usage: /setblockmultglobal <amount>
    
  setmobmult:
    description: Set a multiplier for a mob
    usage: /setmobmult <mob> <amount>

  setmobmultbatch:
    description: Set a multiplier for multiple mobs
    usage: /setmobmultbatch <block,amount;block,amount;...>

  setmobmultglobal:
    description: Set a multiplier for all mobs
    usage: /setmobmultglobal <amount>

  setmobclear:
    description: Clear all extra mob drops
    usage: /setmobclear

  setblockclear:
    description: Clear all extra block drops
    usage: /setblockclear

  viewmobdrops:
    description: view all mob drops with a drop count of over 1 (excluding global extra drops)
    usage: /viewmobdrops

  viewblockdrops:
    description: view all block drops with a drop count of over 1 (excluding global extra drops)
    usage: /viewblockdrops
  This version runs on 1.21! If you want to change the version, you can change the spigot API to your desired version.

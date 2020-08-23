DO NOT TRY THIS ON YOUR LIVE SERVER, THIS IS ONLY A TEST.

I do not own this app, got this source from: https://github.com/ottools, i only did some changes on it.

This is a test version to improve itemEdit, this implement the option "Item price", a need to be done (indeed?) feature to implement new features ingame.

if you find this interesting, check my opentibiabr/otserv-global fork Feat/item-price branch to get this feature implemented ingame, all the server changes already has been made on this branch, except the otb changes with the item prices. (This will take a while xD)
[This fork](https://github.com/marcosvf132/otservbr-global/tree/Feat/Item-Price)
``` lua
Game.getItemWorth(itemid) -- Return item price set on Item Edit.
```


[Image preview](https://prnt.sc/u3yv2c) Showing the new option.

What is ItemEditor?
----

ItemEditor is a program used to edit the OTB data files.

Supported versions:
----

* 8.00 - 12.40

Download
----

[ItemEditor](https://github.com/ottools/ItemEditor/releases) Ottools original ItemEditor

Compiling
----

You can build the project using the provided ItemEditor.sln in Visual Studio 2013 or later.

For linux follow this guide to install mono-devel and mono-complete packages for your distro https://www.mono-project.com/download/stable/, then execute linuxbuild.sh

Icons
----

This project uses [famfamfam silk icons](http://www.famfamfam.com/lab/icons/silk/)

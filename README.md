<img align="right" width="100" height="100" src="https://user-images.githubusercontent.com/37786733/41541140-71602302-731a-11e8-9434-79b3a57292b6.png">

This is a fork of the original [xNode](https://github.com/Siccity/xNode) used by the Bard Dialogue System. \
It comes with [xNode Groups](https://github.com/Siccity/xNodeGroups) plugin pre-installed and features some minor performance and UX tweaks.

Support xNode on [Ko-fi](https://ko-fi.com/Z8Z5DYWA) or [Patreon](https://www.patreon.com/thorbrigsted)

For full Odin support, consider using [KAJed82's fork](https://github.com/KAJed82/xNode)

### xNode
Thinking of developing a node-based plugin? Then this is for you. You can download it as an archive and unpack to a new unity project, or connect it as git submodule.

xNode is super userfriendly, intuitive and will help you reap the benefits of node graphs in no time.
With a minimal footprint, it is ideal as a base for custom state machines, dialogue systems, decision makers etc.

<p align="center">
  <img src="https://user-images.githubusercontent.com/6402525/53689100-3821e680-3d4e-11e9-8440-e68bd802bfd9.png">
</p>

### Key features
* Lightweight in runtime
* Very little boilerplate code
* Strong separation of editor and runtime code
* No runtime reflection (unless you need to edit/build node graphs at runtime. In this case, all reflection is cached.)
* Does not rely on any 3rd party plugins
* Custom node inspector code is very similar to regular custom inspector code
* Supported from Unity 5.3 and up

### Installation

***Via Git URL***
*(Requires Unity version 2018.3.0b7  or above)*

To install this project as a [Git dependency](https://docs.unity3d.com/Manual/upm-git.html) using the Unity Package Manager,
add the following line to your project's `manifest.json`:

```
"com.github.blahnumbers.xnode": "https://github.com/blahnumbers/xNode.git"
```

You will need to have Git installed and available in your system's PATH.

If you are using [Assembly Definitions](https://docs.unity3d.com/Manual/ScriptCompilationAssemblyDefinitionFiles.html) in your project, you will need to add `XNode` and/or `XNodeEditor` as Assembly Definition References.

# Awesome Haxe Targets
A list of all unofficial Haxe compilation targets. These are transpilers that convert Haxe into another language (besides the ones the Haxe compiler officially supports).

All projects are listed here regardless of completion status. They are ordered first by their status, then time since most recent commit. Each is grouped based on the library used to create the target.

Please feel free to open PRs to add, amend, or remove projects!

&nbsp;

# Status

The definition for each "status" icon.

Implementation of the core Haxe API (String, Map, Array, etc.) is a good indicator of the completion of a Haxe target, so that is mostly the deciding factor for each status.

| Icon | Name          | Meaning                                              |
| ---- | ------------- | ---------------------------------------------------- |
| ✅ | Usable          | Many commits and core Haxe API implemented          |
| ⌛ | Usable, But Old | Probably usable, but SUPER old (predates Haxe 4.0)  |
| ❓ | In-Development  | Recent progress or some Haxe API implementation     |
| ❌ | Incomplete      | No recent progress and Haxe API unimplemented       |
| 💀 | Dead            | Not usable and no commits in months                 |

&nbsp;

# Tools

These are libraries that can be used to create your own Haxe targets.

| Name     | Description                                                | Github Link                              |
| -------- | ---------------------------------------------------------- | ---------------------------------------- |
| Reflaxe  | A framework for creating compilation targets using macros. | https://github.com/SomeRanDev/reflaxe    |
| sfhx     | Tools for implementing CustomJSGenerator-based targets.    | https://github.com/YAL-Haxe/sfhx         |

&nbsp;

# Reflaxe-Made Targets

Targets made with Reflaxe.

| Name                 | Language Target | Status | Github Link                                     |
| -------------------- | --------------- | ------ | ----------------------------------------------- |
| Reflaxe/C++          | C++             | ✅ | https://github.com/SomeRanDev/reflaxe.CPP              |
| Reflaxe/GDScript     | GDScript        | ✅ | https://github.com/SomeRanDev/reflaxe.GDScript         |
| Reflaxe/Swift        | Swift           | ❌ | https://github.com/epikowa/haxe_swift
| Reflaxe/C#           | C#              | ❌ | https://github.com/SomeRanDev/reflaxe.CSharp           |
| Reflaxe/Java Sources | Java            | 💀 | https://github.com/EliteMasterEric/reflaxe_javasources |
| Reflaxe/Wren         | Wren            | 💀 | https://github.com/davidbruce/reflaxe.Wren             |

&nbsp;

# Sfhx-Made Targets

Targets made with sfhx.

| Name             | Language Target | Status | Github Link                           |
| ---------------- | --------------- | ------ | ------------------------------------- |
| sfgml            | GML             | ✅ | https://github.com/YAL-Haxe/sfgml         |
| SillySharp       | C#              | ✅ | https://github.com/YAL-Haxe/sillysharp    |
| hxpico8          | Lua             | ⌛ | https://github.com/YAL-Haxe/hxpico8       |

&nbsp;

# Other Targets

Targets made without a specific library.

| Name             | Language Target | Github Link                                    |
| ---------------- | --------------- | ---------------------------------------------- |

&nbsp;

# Transpilers that Target Haxe

Projects that convert a language _into_ Haxe (not including extern generators).

| Name             | Source Target | Status | Github Link                                |
| ---------------- | ------------- | ------ | ------------------------------------------ |
| go2hx            | Go            | ✅    | https://github.com/go2hx/go2hx              |
| node-ts2hx       | TypeScript    | ⌛    | https://github.com/jeremyfa/node-ts2hx      |
| laxe             | Laxe          | ⌛    | https://github.com/SomeRanDev/laxe          |
| haxegen          | Haxe          | ❌    | https://github.com/metincetin/haxegen       |

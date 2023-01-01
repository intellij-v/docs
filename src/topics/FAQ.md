[//]: # (title: FAQ)

### Which IDEs are compatible? Are there any differences?

The plugin is compatible with all IntelliJ-based IDEs starting from the version 2022.3.1, with the following differences
in the sets of the available features:

|                  | Open-source and Educational IDEs<sup>*</sup> | [CLion] (commercial) | [IntelliJ IDEA] Ultimate, [PyCharm] Professional, [GoLand] (commercial) | [WebStorm], [PhpStorm], other commercial IDEs |
|------------------|----------------------------------------------|----------------------|-------------------------------------------------------------------------|-----------------------------------------------|
| Language support | ![][Check]{width=12}                         | ![][Check]{width=12} | ![][Check]{width=12}                                                    | ![][Check]{width=12}                          |
| Debugger         | ![][Cross]{width=12}                         | ![][Check]{width=12} | ![][Check]{width=12}**                                                  | ![][Cross]{width=12}                          |

\* [IntelliJ IDEA] Community Edition, [PyCharm] Community Edition, [PyCharm Edu and IntelliJ IDEA Edu].

\** Requires the
[Native Debugging Support](https://plugins.jetbrains.com/plugin/12775-native-debugging-support) plugin.
LLDB only

### Does the plugin use VLS?

The plugin’s language analysis is implemented from scratch, leveraging the IntelliJ Platform infrastructure for
incremental analysis and indexing.

### Is debugging available?

Yes, you can debug your V code in CLion, IntelliJ IDEA Ultimate, PyCharm Professional, GoLand, and Rider. See the
section on [Debugging](Debugging.md) for details.

### Any tips for migrating from Emacs, Vim, or VS Code?

To bring some of the Emacs keybindings into the IDE, go to **Settings / Preferences | Keymap** and enable the Emacs
keymap.
If you are used to M-x, consider remapping the **Find Action** binding to this shortcut in the Keymap settings. For more
Emacs extensions, try the
[Emacs+Patched](https://plugins.jetbrains.com/plugin/10045-emacs-patched)
plugin.

To get Vim emulation, use the
[IdeaVim](https://github.com/JetBrains/ideavim)
plugin. It adds motion keys, marks, registers, and visual mode commands.
Similarly, you can try out the
[VS Code Keymap](https://plugins.jetbrains.com/plugin/12062-vscode-keymap)
plugin.

[Check]: check_retina_bold_2.png

[Cross]: cross_retina.png

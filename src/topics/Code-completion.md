[//]: # (title: Code completion)

Auto-completion for your V code works as you type, and you can also call it manually from **Code | Code Completion** on the main menu.

Completion works for many places, so for example when you import a module, the IDE will show you a list of available modules to import:

![](import.png){width=700 border-effect="line"}

IntelliJ V takes care of the out-of-scope items when performing completion. This is useful for the cases like adding a module import during a function completion – the corresponding import item is inserted automatically:

![](completion.png){width=700 border-effect="line"}

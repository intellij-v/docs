[//]: # (title: Code reference info)

You can view additional information for most parts of your V code. The IDE shows type information and inlay hints in the
editor as you type. **Quick Documentation**, and **Quick Definition** popups provide even more code insight and can be
accessed via shortcuts and on mouse hover.

## Inlay hints

IntelliJ V shows hints for function parameters and types in the editor inlined with your code.

![](code-reference-info/inlay-hints.png){width=700 border-effect="line"}

You can configure inlay hints in **Settings / Preferences | Editor | Inlay Hints | V**.

![](code-reference-info/hints-settings.png){width=700 border-effect="line"}

> At the moment, the tooltip enable/disable setting is not flexible and turns off all tooltips at once. In the future,
> it is planned to add the ability to configure separately for each type of hints.
> {type=note}

- **Parameter hints**

  Parameter hints show parameter names next to the corresponding arguments in function and method calls. They can help
  you gain insight into a function or method call without having to look at its signature.

- **Type hints**

  Inline type hints next to the corresponding variables are another way to help you read through code faster.

## Type info

In addition to type hints, you can get type information for an element or expression by pressing <kbd>
Ctrl+Shift+P</kbd>:

![](code-reference-info/type-info.png){width=700 border-effect="line"}

## Quick documentation

With the **Quick Documentation** popup, you can view documentation for any code element (including library functions)
right in the editor: just hover over the element or place the caret on it and press <kbd>Ctrl+Q</kbd>.

![](code-reference-info/quick-documentation.png){width=700 border-effect="line"}

## Quick definition

To view the implementation or declaration of an element at caret without leaving the current file, call the **Quick
Definition** popup by pressing <kbd>Ctrl+Shift+I</kbd>:

![](code-reference-info/quick-definition.png){width=700 border-effect="line"}
[//]: # (title: Code reference info)

You can view additional information for most parts of your V code. The IDE shows type information and inlay hints in the
editor as you type. **Quick Documentation**, and **Quick Definition** popups provide even more code insight and can be
accessed via shortcuts and on mouse hover.

## Inlay hints

IntelliJ V shows hints for function parameters and types in the editor inlined with your code.

![](inlay-hints.png){width=700 border-effect="line"}

You can configure inlay hints in **Settings / Preferences | Editor | Inlay Hints | V**.

![](hints-settings.png){width=700 border-effect="line"}

- **Parameter hints**

  Parameter hints show parameter names next to the corresponding arguments in function and method calls. They can help
  you gain insight into a function or method call without having to look at its signature.

- **Type hints**

  Inline type hints next to the corresponding variables are another way to help you read through code faster.

- **Evaluated enum values**

  Show the value that the enum field has.

  ![](enum-hints.png){width=700 border-effect="line"}

- **Method chain hints**

  Show the result for each individual method call in the call chain.

  ![](method-chain-hints.png){width=700 border-effect="line"}

## Type info

In addition to type hints, you can get type information for an element or expression by pressing <kbd>
Ctrl+Shift+P</kbd>:

![](type-info.png){width=700 border-effect="line"}

## Parameter info

The **Parameter Info** popup shows the names of parameters in method and function calls.
IntelliJ V automatically shows a popup with all available method signatures within 1 second (1000 milliseconds) after
you type an opening bracket in the editor, or select a method from the suggestions list.
You can explicitly invoke the popup if it has closed or if your IDE is configured not to show the popup automatically.
To do so, press <kbd>Ctrl + P</kbd> (or click **View | Parameter Info**).

![](parameter-info.png){width=700 border-effect="line"}

## Quick documentation

With the **Quick Documentation** popup, you can view documentation for any code element (including library functions)
right in the editor: just hover over the element or place the caret at it and press <kbd>Ctrl+Q</kbd>.

![](quick-documentation.png){width=700 border-effect="line"}

> If you don't want the Quick **Documentation popup** to appear on mouse hover, go to
> **Settings / Preferences | Editor | Code Editing | Quick Documentation** and clear the
> **Show quick documentation on hover** checkbox. Alternatively, click App actions
> more in the popup and disable the **Show on Mouse Move** option.
> {type=note}

## Quick definition

To view the implementation or declaration of an element at caret without leaving the current file, call the **Quick
Definition** popup by pressing <kbd>Ctrl+Shift+I</kbd>:

![](quick-definition.png){width=700 border-effect="line"}
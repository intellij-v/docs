[//]: # (title: Refactorings)

> Refactorings are now in a rudimentary state and will be improved during beta testing.
> {type=note}

IntelliJ V provides the following refactorings for your V code:

- [Rename](#rename) (<kbd>Shift+F6</kbd>)
- [Introduce variable](#introduce-variable) (<kbd>Ctrl+Alt+V</kbd>)

To quickly view the list of the available refactorings for the current context, call **Refactor | Refactor This** (<kbd>Ctrl+Alt+Shift+T</kbd>):

![](refactor-this.png){width=700 border-effect="line"}

## Rename

One of the most frequently used refactorings, **Rename** (<kbd>Shift+F6</kbd>), renames any symbol (except module names for now) and automatically corrects all the references in your code. For example, when you rename a struct field, the corresponding usages in the code are renamed as well.

You can rename symbols in-place or use a dialog with a preview.

> For more information on the **Rename** refactoring, refer to [this page](https://www.jetbrains.com/help/idea/rename-refactorings.html) of the Intellij IDEA documentation.
> {type=note}

## Introduce variable

**Introduce Variable** (<kbd>Ctrl+Alt+V</kbd>) puts the result of an expression into a variable. It declares a new variable and uses the expression as an initializer. The original expression is replaced with the new variable.

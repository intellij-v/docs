[//]: # (title: Code generation)

Your IDE with IntelliJ V provides multiple ways to generate V code constructs and recurring elements. There are many intention actions and quick-fixes which can help you quickly insert the required code based on the current content. You can also use live templates (both custom and pre-generated) and postfix completion.

## Intentions and quick-fixes

When the IDEA with IntelliJ Rust finds a way to fix, improve, or optimize your code, it displays either a yellow bulb icon ![][intention-bulb] (intention suggested) or a red bulb with an exclamation mark ![][quick-fix-bulb] (quick-fix suggested) in the editor next to the corresponding line.

Click the bulb icon or press <kbd>Alt+Enter</kbd> to view the available intentions:

![](intention.png){width=700 border-effect="line"}

You can find the full list of V intentions and adjust them if necessary in **Settings / Preferences | Editor | Intentions | V**:

![](intentions-settings.png){width=700 border-effect="line"}

See also full list of V inspections in **Settings / Preferences | Editor | Inspections | V**:

![](inspections-settings.png){width=700 border-effect="line"}

## Live templates

Use live templates to insert common constructs into your code, such as loops, conditions, various declarations, or print statements. You can explore and customize the list of live templates in **Settings / Preferences | Editor | Live Templates | V**:


Press <kbd>Ctrl+J</kbd> to check which templates are available in the current context. If you already know the abbreviation, just start typing it, choose from the list of suggestions, and then press <kbd>Tab</kbd> to navigate between the template variables:

![](live-templates-settings.png){width=700 border-effect="line"}

> You can also create custom live templates, see [Creating live templates](https://www.jetbrains.com/help/idea/creating-and-editing-live-templates.html) in the IntelliJ IDEA documentation.
> {type=note}


## Postfix completion

Postfix completion helps you reduce backward caret jumps as you type. You can transform an already-typed expression into a different one based on a postfix you type after the dot.

For example, type `.var` after an expression (or select it from the completion suggestions list) to insert variable creation:

![](var-template-example.png){width=500 border-effect="line"}

You can check and adjust the list of postfix templates in **Settings / Preferences | Editor | General | Postfix Completion | V**:

![](postfix-completion-settings.png){width=700 border-effect="line"}

[intention-bulb]: app.actions.intentionBulb.svg
[quick-fix-bulb]: app.actions.quickfixBulb.svg

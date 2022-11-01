[//]: # (title: Minor editor features)

IntelliJ V adds a lot of minor convenience features that make it easier to work with code.

## Foldings

The plugin provides a wide opportunity for code folding. You can fold most constructions with several lines of code:

![](foldings.png){width=700 border-effect="line"}

## Code commenting

Using the shortcut <kbd>Ctrl + /</kbd> you can comment out the current line or selection with inline comments.
Shortcut <kbd>Ctrl + Shift + /</kbd> will comment out the selected fragment with block comment.

![](comment-line.png){width=700 border-effect="line"}

## Code vision for VCS

Above functions, structures, interfaces, and so on, you can see information about those who edited the code.

![](code-vision-vcs.png){width=700 border-effect="line"}

## Spellchecking

The plugin supports spell checking in string literals and identifiers.

![](spellchecking.png){width=700 border-effect="line"}

## Exit points

The plugin highlights all function exit points
(`panic` and `exit` calls as well) when you position the caret at one of them or on the function name.

![](exit-points.png){width=700 border-effect="line"}

## Declaration up/down mover

The plugin provides a convenient way to re-arrange the functions of structs, etc.

Press <kbd>Ctrl + Shift + Up/Down</kbd> to move the declaration up or down.

You can also move single line of code with <kbd>Alt + Shift + Up/Down</kbd>.

## Line marker for recursive calls

The plugin highlights all recursive calls with a special gutter icon:

![](recursive-call.png){width=700 border-effect="line"}


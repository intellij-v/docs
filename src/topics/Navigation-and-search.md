[//]: # (title: Navigation and Search)

You can quickly navigate through your V code, as well as through the IDE elements, using various actions and popups.

## Search everywhere

**Search everywhere** is the easiest way to find anything in the IDE – a code item, action, or UI element.
Press <shortcut>Shift</shortcut> twice to open the search window. By default, the IDE displays the list of recent files.

Completion also works in this dialog to help you find the desired item, and you can narrow the search by setting the
required scope.

![](search-everywhere.png){width=700 border-effect="line"}

## Find usages

The **Find Usages** action helps you search for the references of a code element across the codebase. You can search
only in a single file, in the whole project, or create a custom scope for your search.

### Find usages in file

1. In the editor, place the caret at a symbol you want to find.

2. By default, the IDE automatically highlights all found usages in the file:

   ![](local-find-usages.png){width=700 border-effect="line"}

   To turn this highlighting off, go to **Settings / Preferences | Editor | General | Code Editing** and clear the
   **Highlight on Caret Movement | Usages of element at caret** checkbox.

   When automatic highlighting is disabled, you can call Find Usages for a file by pressing <kbd>Ctrl+Shift+F7</kbd> or
   selecting **Edit | Find Usages | Find Usages in File** from the main menu.

   > Use the <kbd>Ctrl+Alt+Down</kbd> and <kbd>Ctrl+Alt+Up</kbd> shortcuts for navigation between usages in a file.
   > {type=note}

### Search for usages in a project

1. Select a symbol, then right-click it and choose **Find Usages** from the context menu, or press <kbd>Alt+F7</kbd>.
2. The IDE shows the results in the **Find** tool window. In this window, you can filter and group the results, and jump
   back to the source code:

   ![](global-find-usages.png){width=700 border-effect="line"}

## Go To actions

There are several Go To actions you can use to quickly navigate through your code.

![](goto.png){width=700 border-effect="line"}

- **Declaration or Usages** (<kbd>Ctrl+B</kbd>) - jumps to the item's declaration or shows when a list usages when on a
  declaration.

- **Definition (Implementation)** (<kbd>Ctrl+Alt+B</kbd>) - shows the list of implementations for interfaces. This
  action is also available via a gutter icon:

  ![](interface-implementations.png){width=700 border-effect="line"}

- **Go to Super Method** (Disabled for now) - navigates from an members of interface or interface implementation to
  interface themselves.

## File structure

You can explore the structure of the currently opened file in the **Structure** tool window or in a popup.

- To open the **Structure** tool window, select **View | Tool Windows | Structure** from the main menu or press <kbd>
  Alt+7</kbd>.

  ![](structure-view.png){width=600 border-effect="line"}

- To view the file structure in a popup, select **Navigate | File Structure** from the main menu or press <kbd>
  Ctrl+F12</kbd>.

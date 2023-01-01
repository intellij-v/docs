[//]: # (title: Code analysis)

With IntelliJ V, you have static code analysis inside IDE with builtin inspections that work as you type.

## Inspections

Inspections detect and help to correct anomalous code before you compile it. This includes various problems like potential bugs, spelling problems, or overall code structure issues.

> Note that not many inspections have been implemented at the moment due to lack of time, 
> inspections will be added in the course of further development.
> {type=note}

By default, most of the V inspections work on-the-fly and provide quick-fixes to be applied right away. Find a few examples below:

- Naming conventions:
    ![](naming-convention-example.png){width=600 border-effect="line"}
- Variable redeclaration:
    ![](variable-redeclaration-example.png){width=700 border-effect="line"}

You can also run inspections on demand by calling **Code | Inspect Code** from the main menu. In this case, the results are shown in a separate window, from which you can apply quick-fixes to a single case or to several cases at a time:

![](batch-mode.png){width=700 border-effect="line"}

### Inspections settings

To configure the inspections, go to **Settings / Preferences | Editor | Inspections | V**:

![](inspections-settings.png){width=700 border-effect="line"}

### Scopes

Inspections can scan your code in all project files, or only in some specific scopes (for example, only in production code, or in modified files):

![](scopes.png){width=500 border-effect="line"}

### Severity levels

Every inspection has a configurable severity level — the extent to which a problem can affect your code:

![](severity.png){width=500 border-effect="line"}

Severities are highlighted differently in the editor so that you can quickly distinguish between critical problems and less important things. Click **Edit severities** to configure the highlighting scheme. In the **Severities Editor** dialog, you can also delete or create new severity levels.

### Enabling/disabling/suppressing inspections

You can turn the inspections on and off in the settings (clear or set the corresponding checkbox), or in the editor (click the bulb icon or press <kbd>Alt+Enter</kbd>):

![](enable-disable-inspection.png){width=700 border-effect="line"}

You can either disable the inspection or suppress it. For some cases, you will see the options to suppress the inspection for a file or statement.

The **Suppress all inspections for statement** option inserts a `// noinspection ALL` comment, disabling all the inspections for the current item.

**Suppress for statement** inserts `// noinspection InspectionName`, this way disabling only the current inspection for the piece of code:

![](suppressed-inspection.png){width=700 border-effect="line"}

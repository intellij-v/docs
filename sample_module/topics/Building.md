[//]: # (title: Running)

Use one the following options to run project:

- Click the gutter icon next to the **main** function:

  ![](run-gutter.png){width=700 border-effect="line"}

- Use the context menu in Project view (for a module or the whole project):

  ![](run-context-menu.png){width=700 border-effect="line"}

When a build action is called, the IDE opens the **Build** tool window to display the process and the result of building on the **Build Output** tab:

![](build-tab.png){width=700 border-effect="line"}

If the build completes successfully, the IDE will run the resulting binaries and open **Run** tool window to display output:

![](run-tab.png){width=700 border-effect="line"}

Use icons on the tab's toolbar to stop or rerun the build:

![](rerun.png){width=400 border-effect="line"}

## Configuration settings

You can flexibly customize how your project builds and runs. To do this, use the configuration settings.
You can find them in the main menu in **Run | Edit Configurations...**:

![](configurations-settings.png){width=700 border-effect="line"}

By default, when you run a project build, it builds the project from the entire folder, not just from the current file.
To change this in **Run kind** select _File_ and click **Apply**.
Now when you run the build, it will only build the current file.

If you don't want the IDE to run the resulting binary after the build, clear **Run after build** checkbox.

You can configure launch arguments by specifying them in the **Program arguments** field. Also you can configure additional build parameters by specifying them in the **Build arguments** field.

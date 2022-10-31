[//]: # (title: Quick Start Guide)

#### Prepare the environment

- Install V from [source](https://github.com/vlang/v#installing-v---from-source-preferred-method) or other [installation options](https://vlang.io).

> Make sure you run `sudo v symlink` (`.\v.exe symlink` on Windows) command after installing V. This will help the plugin determine the paths to V.

## Install / update the plugin

#### Stable build

Not yet available. See next section.

#### Nightly build (until beta release)

1. Go to **Settings / Preferences | Plugins** in your IDE.
2. Click ![][gear] and then click **Manage Plugin Repositories**.
   
   ![](quick-start-guide/plugin-repositories.png){width=700 border-effect="line"}
3. In the **Custom Plugin Repositories** dialog, click ![][add] and specify the following repository URL:
    ```
    https://plugins.jetbrains.com/plugins/nightly/8182
    ```
   ![](custom-plugin-repositories.png){width=700 border-effect="line"}
4. Click **OK** in the **Custom Plugin Repositories** dialog.
5. Switch to **Marketplace**, and search for _Vlang_:
6. Click **Install** and restart the IDE.

## Create new project

With the plugin's project wizard, you can quickly create new V project.

1. Go to **File | New | Project** (**File | New Project**) or click **New project** on the welcome screen.
2. Select **V** from the list in the left-hand pane.
3. Specify the project name, location, and toolchain parameters:
   ![](new-project.png){width=700 border-effect="line"}
4. Click **Create** when ready, and the IDE will generate a ready-to-go stub project for you:
   ![](new-project-created.png){width=700 border-effect="line"}

## Open existing project

1. Go to **File | Open**) or click **Open** on the welcome screen.
2. Select the root directory of the project and click **OK**.
3. When you open an existing project, a notification will be shown that the toolchain is not configured:

   ![](toolchain-not-configured.png){width=700 border-effect="line"}

4. To set up the toolchain, click **Setup V toolchain**.

   This will open the settings dialog:

   ![](project-settings.png){width=700 border-effect="line"}

   If V was added to the **PATH** with the `v symlink` command, then the plugin will automatically set
  all the necessary paths.

   If the plugin could not find paths to the toolchain, select them manually.

5. Click **Apply** to finish setup and wait until the IDE finishes indexing the standard library.

## Clone a repository

1. Go to **VCS | Get from Version Control** or click **Get from VCS** on the welcome screen.

   If there's already a Git project opened, select **Git | Clone** from the main menu.
2. Provide the repository URL and specify the destination directory, then click **Clone**:

   ![](clone-repository.png){width=700 border-effect="line"}
3. After the project opens, follow steps 4-6 from **Open existing project**.


## Project settings

For general project settings, navigate to **Settings / Preferences | Languages & Frameworks | V**:

![](project-settings/project-settings.png){width=700 border-effect="line"}

Use the **Vfmt** node to adjust the Vfmt formatter settings:

![](project-settings/vfmt-settings.png){width=700 border-effect="line"}

## Run 

To run a selected target, do one of the following:

- Select **Run** from the gutter menu next to the program entry point:
  
   ![](run-gutter.png){width=700 border-effect="line"}

- Press <kbd>Ctrl/Command + Shift + R<kbd>

## Debug

No available for now. Work in progress.

[gear]: app.general.gearPlain.svg
[add]: app.general.add.svg

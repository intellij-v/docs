[//]: # (title: Code style and formattings)

IntelliJ V helps your code stay compliant with style guidelines and naming conventions.

## Configure code style for V

The only style in the plugin is the style used in V itself with **v fmt**. There is currently no option to customize a different style.

## Code formatting

The plugin uses the **v fmt** utility built into the language to format the code.

> Reformatting selected code is not yet available.
> {type=note}

To customize **v fmt** calls, navigate to **Settings / Preferences | Languages & Frameworks | V | Vfmt**.

![](code-style-and-formattings/vfmt-settings.png){width=700 border-effect="line"}

- You can specify additional arguments for **v fmt**.
- And also custom environment variables if needed.

If you want the plugin to keep your code formatted, then select **Run vfmt on Save**.

### Keep formatting on commit

> This feature is not yet available.
> {type=note}

You can configure the plugin to run **v fmt** on each commit.
This way, you can be sure that your code is always formatted properly.

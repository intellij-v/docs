[//]: # (title: Building)

Use one the following options to run project:

- Click the gutter icon next to the **main** function:

  ![](run-gutter-icon.png){width=700 border-effect="line"}

- Use the context menu in file:

  ![](run-context-menu.png){width=700 border-effect="line"}

- In IntelliJ IDEA, you can also run the current file through predefined **Current File** run configuration:

  ![](predefined-run-current-file.png){width=700 border-effect="line"}

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

Let's look at what each field is responsible for:

1. **Run kind**: chooses how to run the project, the default is **Directory**, so V will build the whole module from folder and run it. If you only want to run one file then select **File**.
2. **Output directory**: sets the path where the compiled binary will be placed. By default, this is the **bin** folder at the root of the project.
3. **Run after build**: determines if the project will run after build. Enabled by default.
4. **Working directory**: sets the working directory for the project to run. By default, this is the project root.
5. **Environment**: sets the environment variables for the project to run. The default is empty.
6. **Production build**: determines whether the project will be built in production mode. In this mode, the project takes longer to build because the compiler applies various optimizations to make the program faster. Disabled by default.
7. **Emulate terminal in output console**: determines if the built-in IDE console will emulate a real terminal when it starts up. This can be useful if you are running a program that interacts with the cursor in the terminal, such as moving the cursor down or left. Enabled by default.
8. **Build arguments**: sets the build arguments. Use this field if you want to pass extra arguments to the compiler, for example if you want to pass the `-no-bound-checks` option when building. The default is empty.
9. **Program arguments**: sets the command line arguments to be passed when running the binary. Use this field if your program takes some arguments, such as `./your-program -f file.txt`. The default is empty.

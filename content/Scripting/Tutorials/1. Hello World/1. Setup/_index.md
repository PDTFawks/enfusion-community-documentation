Goal: Print “Hello World” to the “Output box” when a scenario is started.

To do this we are going to override the “OnGameStart” method from the “SCR_GameCoreBase” class.
The class is in the “scripts\Game\GameCore” directory. So we will recreate that path.

In the Workbench “Resource Browser”:
1. Click on your project name (“EnscriptTutorial” in this case).
2. Click “+Create”
3. Then click “folder”
4. Name the folder “scripts”.
5. Click on the “scripts” folder you made.
6. Repeat steps 2-5 changing “scripts” to the correct folder name.
7. Finally we need to create a “Modded” folder for our script to go in.
7.1 This keeps everything nice and tidy and ensures there’s no confusion between the original and ours.

When you’re done it should look like this:
```
>ArmaReforger
>core
>EnscriptTutorial
  >scripts
    >Game
      >GameCore
        >Modded
>profile
```

Now create a script file ```(“+Create” > “Script”) and name it “SCR_GameCoreBase”```.
{{< hint type=tip >}}
The reason we name it `“SCR_GameCoreBase”` apart from maintaining consistency with vanilla is so we can more easily figure out what changes a particular project has made to certain classes.
{{< /hint >}}

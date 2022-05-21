## Setup
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
![ScriptEditor](https://i.imgur.com/zp9Ir7G.png)

Now create a script file (“+Create” > “Script”) and name it “SCR_GameCoreBase”.
The reason we name it the same is: so that we know exactly what we are changing. And so  6 months down the road, we aren’t looking through 20 different files trying to figure out where we changed it, we can find it.

Now to edit the script, double click on it. This will open the script editor.

Now we need to create the class, remember since we are modifying a vanilla class we need to use the “modded” keyword. Then we need to create and override the “OnGameStart” method (remember it’s void!).
```c++
modded class SCR_GameCoreBase
{
  override void OnGameStart()
  {

  }
}
```

Then we need to make it print “Hello World” and make sure we don’t break stuff (you read the documentation right?)
```c++
modded class SCR_GameCoreBase
{
  override void OnGameStart()
  {
    super.OnGameStart();
    Print("Hello World");
  }
}
```
{{< hint type=caution >}}
The `super` keyword is extremely important when overriding classes.
{{< /hint >}}

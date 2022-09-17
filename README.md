# In *Unity* scene

  - The *horses* need to be *child object* of the *Table object*.
  - *Horses* need to have the *animator component*.
  - The *maincanvas* is the canvas that user interacts with to start game.
    - Rename this objects in the scene.
       - Button to start game = "StartGame".
       - Timer text when the game starts = "Timer".
       - Speed text when the game starts = "Speed".
       
![image](https://user-images.githubusercontent.com/49632606/190878238-44cf744e-d02f-427e-9719-240f3b7e68d2.png)
![image](https://user-images.githubusercontent.com/49632606/190878251-b4856dd6-41aa-4aeb-ab47-90e7c24606e4.png)

 # In *Visual Studio*
 To declare location for outputs
 From the tool-bar go to *Project -> Dll_Project Properties -> Build Events -> Post-build event command line*
  - copy "$(TargetDir)$(ProjectName).dll" "**YOUR PREFFERED LOCATION FOR OUTPUT** \$(ProjectName)dll.bytes"
  - copy "$(TargetDir)$(ProjectName).pdb"  "**YOUR PREFFERED LOCATION FOR OUTPUT** \$(ProjectName)pdb.bytes"
  
![image](https://user-images.githubusercontent.com/49632606/190878290-31bb8404-c262-4f18-8c86-fae464425c16.png)

## About the "fix" cfg's
Right, so after the update today (Oct 17th) valve removed the ability to "desubtick" your movement. This means that your movment command will execute randomly anywhere from tick 1 to (rumored) tick 20. The result of this creates issues like random jump heights and inconsistent W+JT smokes.
I'm looking for a fix for the WJT smokes however these cfg's force the command to be executed on the first tick everytime again. 

- To use them download all the "fix" cfg's and place them into your cfg folder.
- In your autoexec.cfg find anywhere you had your previous alias binds or "+forward;clear" binds and update them to be alias'ed like the following
- alias +<movement>fix "exec <movement>fix"
- alias -<movement>fix "-<movment>"
- bind <key> "+<movement>fix"
- This will again desubtick your movement
 
 ## Useage Tutorials  
- [Autoexec and Prac](https://youtu.be/OiruKLO1WUg)
### Map Spawns
- Load Up the map in prac mode
- Exec the map spawn & side you want to practice
- numbers 1-x tp to you to the spawn location just like if you were doing endround
- lineupX will tp you facing the lineup to instant smokes whatever it might be from that spawn point
- Anubis Specific -> eboxlineupx and houselineupx for instant smokes on both of those

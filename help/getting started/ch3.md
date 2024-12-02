# ch3
---- 
## Create Design Pattern

## Active Object
### Dynamic Events To and from process
This design pattern makes the class become active. This means that a standalone process starts when you create an object can read and write the objects attribute.

Add a command to a process
![][image-1]
The process.vi will handle al the que and the generated users events. Within this case statement the behavior can be defined. 

Within this newly created method a custom command generating a user event can be given.
![display command][image-2]

This command can be defined within the process.vi to add some behavior when executing this method. 

![Process VI Command][image-3]

---- 
\*\*Walk-Through of design pattern

\*\*How to make your own design patterns

[image-1]:	images/fig_command.png
[image-2]:	images/display_command.png
[image-3]:	images/process_vi_command.png
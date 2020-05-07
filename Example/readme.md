This is a Hello World example for users to get started. The PLC program will just keep the output (lamp) on for 2 seconds after the button is pressed.

The interface.cfg from this folder should be used since it matches the configuration of the UDP Send and Receive blocks in the model. This was configured for a system that is running everything (OpenPLC, Simulink and SimLink) on the same computer (localhost).

![alt text](https://github.com/thiagoralves/OpenPLC_Simulink-Interface/raw/master/Example/Capture.png)


Files:  
Hello_World.xml -> PLC ladder diagram. Opens on PLCOpen Editor  
hello_world.slx -> Simulink 2017 model  
hello_world_2012b.slx -> Same model compatible with older versions of Simulink (doesn't support dashboard elements)  
interface.cfg -> File to be used to configure SimLink. Must be in the same folder of the executable

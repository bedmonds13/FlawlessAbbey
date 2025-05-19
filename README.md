# FlawlessAbbey

Hey there !

This is my submission for the UE5 Programmer position.

For this test you can walk up to different objects in the world and will be prompted to interact with them.
Based on the object it can be either picked up or trigger the dialogue sequence from that item. The inventory can be opened by pressing the 'I' key and can only be closed through the 'ESC' key or pressing the 'X' icon in the top right corner. Items can swap places between each other and hovering over the larger right hand slot will display the image.


All objects can be triggered through an "Interact" interface. This allows for the UI prompt to take in any actor and interact with it without knowing specific information about the object. My design for the pickup system separate two objects through being a 2d sprite or a static mesh, both using a sphere collision to add the interact prompt to your screen. This allows for efficient adding of new items and for the inventory menu to know how to do change functionality of an inventory slot (e.g. the forget note button) or the large viewport slot (e.g. using a 3D rotatable mesh or an enlarged sprite). Rotating objects can be done through the 'Q' and 'E' key

 

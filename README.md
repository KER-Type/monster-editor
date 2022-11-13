You can create your own Monster.
To do that you have to follow the next instruction:

Sprite:[Texture's path]  
Details of the monster's texture  
{  
&nbsp;&nbsp;Width:[Value]  
&nbsp;&nbsp;Heigth:[Value]  
&nbsp;&nbsp;Top:[Value]  
&nbsp;&nbsp;Left:[Value]  
&nbsp;&nbsp;Shift:[Value]  
&nbsp;&nbsp;MaxShift:[Value]  
&nbsp;&nbsp;MinShift:[Value]  
&nbsp;&nbsp;Scale:[Value]  
}  
[Action list]  
(U -> Up --> monster go up)  
(D -> Down --> monster go down)  
(L -> Left --> monster go on the left)  
(R -> Right --> monster go on the right)  
(S -> Shoot --> monster shoot a laser)  
(20 D --> the monster will execute the Down action 20 times, this can be use with all actions)  

## Example:

Sprite:../Textures/Globur.gif   
Width:33  
Heigth:36  
Top:0  
Left:66  
Shift:0  
MaxShift:99  
MinShift:99  
Scale:3  
20 D  
S  
20 D  
S  
20 D  
S  
20 D  
S  
20 U  
S  
20 U  
S  
20 U  
S  
20 U  
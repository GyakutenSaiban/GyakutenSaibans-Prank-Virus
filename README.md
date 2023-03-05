# GyakutenSaibans-Prank-Virus
Simply just a prank that makes it look like you have a virus.

To edit the prank, unzip "Gyakuten's Prank Virus.zip", go in the folder, select "cool shit in under 700 KB!", then select "Inner Machinations". Select "BRAIN POWER.vbs" and edit it in Notepad.
Here's a template. X=MsgBox("Message text",0+64,"Heading").

---------------MESSAGE BUTTONS---------------
These are before the plus.
0 = OK
1 = OK/Cancel
2 = Abort/Retry/Ignore
3 = Yes/No/Cancel
4 = Yes/No
5 = Retry/Cancel

---------------MESSAGE ICONS---------------
These are after the plus.
0 = No icon
16 = Critical
32 = Help
48 = Warning
64 = Information

You can also do this:

do
X=MsgBox("Message text",0+64,"Heading")
loop

I recommend that you use the loop at the end because it loops forever. Well, that is until you pull up Task Manager and press "End task".

# MekWars-Apocalypse

INTRODUCTION
------------
This is the a client/server platform for MekWars - Apocalypse. It bundles two pieces of software, MekWars and MegaMek 
in one package alongside many original files, e.g. graphics, unit files and more.

MegaMek is a version of BattleTech that you can play with your friends 
over the internet.  

MekWars is a platform for matchmaking and providing deeper aspects for MegaMek, 
like having/managing a hangar and matchmaking.

They are both written in Java.  


INSTALLING OR UPDATING YOUR JAVA RUNTIME
----------------------------------------
If your system did not come with a Java VM, or you need to update your Java
VM, here are some links.

Sun Java (Linux, Solaris, Windows):
http://java.sun.com/j2se/downloads.html

Mac OSX 10.1 and above:
Java updates are included in OS updates for 10.1 and above.  There is no
external way to update your Java VM.

Earlier Mac OS versions:
http://developer.apple.com/java/download.html

GCJ/Gnu classpath (Linux):
Of interest to experienced developers, there may be some
compatibility problems.
http://gcc.gnu.org/java/

Microsoft VM (Windows):
Microsoft no longer makes their VM available for seperate download.
This version of MegaMek uses features not supported by the Microsoft JVM.

IBM VM:
MegaMek seems to react badly to this VM - it is not recommended.

DIFFERENCES BETWEEN THE BOARD GAME AND MEGAMEK
----------------------------------------------
Although MegaMek tries to be faithful to the original board game rules, in
some cases, due to technical or design limitations, this is not possible.
These differences are not considered "bugs."  If you spot any more 
discrepancies, please contact the author (see "CONTACT" below.)

- If the line of fire lies along the edge of two hexes, in the board game,
    the defender chooses which hex to use.  Instead, MegaMek chooses the
    hex that most favors the defender.
    
- When punching, you automatically punch with both arms, if possible.  This
    means you can not punch two different targets in the same round.
    
- When kicking, you automatically use the leg with the better chance to hit.

- There are several situations, notably death from above, where a unit is
    displaced out of a hex, and that unit's owner may pick the hex to move to.
    MegaMek currently picks the hex for you, choosing high elevations over low
    ones, to avoid falling damage.
    
- Some more that I've forgotten...




CONTACT & FURTHER INFORMATION
-----------------------------
For more information, visit the websites at
http://shack.battletek.org
http://mekwars.sourceforge.net:
http://megamek.sourceforge.net/

For more information about the BattleTech board game, visit it's website at:
http://www.classicbattletech.com/


To contact the author with bug reports, suggestions, or anything else, visit 
the contact page on the MegaMek website, or send email to bmazur@sev.org



COPYRIGHT & LICENSE INFORMATION
-------------------------------
This client consists solely of free software (GPL v2).
  
This program is distributed in the hope that it will be useful, but 
WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY 
or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License 
for more details.

BattleTech, Mech, BattleMech and MechWarrior are Registered Trademarks of 
WizKids, LLC.  Original BattleTech material Copyright by  WizKids, LLC.  
All Rights Reserved.  Used without permission. 

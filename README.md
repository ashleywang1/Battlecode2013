Battlecode2013
==============

I'll try to make the setup descriptions as detailed as I can - I'm assuming you're a beginner at Java and battlecode.

source : (http://battlecode.mit.edu/2008/docs/software.html):

Overview
==============

The BattleCode software consists of three major components:

the player library/API: these are the classes that you will import and build against when writing a player.

the server: this is the software that computes BattleCode matches. For most users, the server will run transparently, so you don't have to worry about it. However, advanced server setups are possible, allowing you to compute matches on one machine and view them on another.

the client: this is the software that displays BattleCode matches. For most users, the client will automatically create a server for running a match and display that match as it computes. The client also plays match files like those from scrimmage matches and the tournaments.

System Requirements
==============

The BattleCode software requires:


1) Java development kit - Jdk1.7.0_45
click this ---> http://www.oracle.com/technetwork/java/javase/downloads/index.html
save the Jdk1.7.0_45 to C:/Program Files (x86)
Install

2) Apache Ant
click this ----> http://apache.mirrors.tds.net//ant/binaries/apache-ant-1.9.3-bin.zip
save to C:/Program Files (x86)
Read this (http://ant.apache.org/manual/index.html) and install it somehow. Email me if you can't figure it out.

3) Eclipse IDE
click here --->http://eclipse.org/downloads/
GET THE 32-BIT VERSION THE 64 BIT VERSION breaks EVERYTHING
Save the folder anywhere you want, just remember it

4) Battlecode Installer
click here---> http://www.battlecode.org/
Download the installer

Installation
==============

After you have installed the software, open Eclipse and choose "File" -> "New" -> "Project..." and choose "Java Project from Existing Ant Buildfile". Navigate to the build.xml in your Battlecode install folder and use this one. Name your project, or leave it as the default and click 'Link to build file in the filesystem' and click 'Finish'. Alternatively, you can use "Java Project from Existing Source" and then in the import screen click the (+) next to teams, and exclude from the build path the players provided by the devs (such as neutralplayer, basicplayer et. al).

When it finishes, Eclipse will add the "teams" folder as a source folder and add the included jar files to your build path. (If you installed Ant, you'll see a lots of files beginning with "ant-" on your build path. You can safely remove them from your build path, but don't delete them!) You can begin developing a player.

When you're ready to run a match, right click the "build.xml" file in your project root directory and choose "Run As" -> "Ant Build". You can re-run the match software by choosing the external tools runner in the Eclipse toolbar (the green-and-white run icon with a small bag beneath it).

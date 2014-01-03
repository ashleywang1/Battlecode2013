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

JDK 5.0 or greater
an operating system that supports Java (Windows, Mac OS X, Linux, Solaris, including Athena)
The following hardware is recommended for best performance:

at least 512 MB of RAM
a video card with OpenGL hardware acceleration
Ensure that you have the correct version of the Java VM and compiler installed on your machine. You can do this at a command prompt with:

  javac -version
  java -version

Apache Ant
==============

Apache Ant is a Java-based build system similar in theory to UNIX make. This year, we are providing an Ant build file to conveniently compile players and run the BattleCode software.

If you are using the BattleCode installer, you have the option of including Ant in your BattleCode installation. If you already have Ant set up on your system, you don't need to include it in the installation.

You are not required to use the Ant build script, though it's been designed so that you can get up and running quickly and easily.

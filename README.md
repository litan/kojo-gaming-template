# kojo-game

This project provides a templete to help you build desktop and android versions of your game (that is built with kojo-gaming).

To get you running, this project already contains a sample `lunar lander` game. What you want to do is to replace `lunar lander` with your own game.

High level steps:
- remove lunar lander assets from the assets dir. After this, the dir should contain libgdx.png and OepnSans.ttf
- add your game assets to the assets dir
- replace `/home/lalit/work/kojo-gaming-template/core/src/main/scala/net/kogics/kojo/game/lander.scala` with your (one or more) scala files. One of these files should define a `Main` class
- run `:lwjgl3:distZip` to build your desktop distribution
- run `:android:assembleDebug` to build your android apk

# Outline
## Overview of GPU's
  People have been using comptuers to display pretty pictures for a very long time. I am going to give a brief
  overview of the history of consumer computer graphics. 
## Pixel Based (Little to no acceleration)
  For most of the history of comsumer machines the resolution of dispayed images was limited by how much memory the 
  computer had. For example a 1080p image takes up 1 Megabyte of space. Up until 1985 it would be impossible to store
  that much data in a IBM PC's memory (Irvine,29). Consumer computers graphics system worked around memory limitations
  by limiting the resolution and number of colors. Limiting the colors is especially helpfull because each additional color
  requires more space inorder to encode the data. One example system is VGA (Video Graphics Array). VGA is still present in
  the form of the connecture used for it, the VGA connector. VGA has a resolution of 320x200 Pixels with 256 possible colors (Ferraro, 257). This video mode is very limiting because the programmer has to manually place every pixel on the screen and this takes the computer quite a bit of time to go through and change each and every pixel. It could be much faster to 
  have some hardware that could do some work for the centeral processing unit.
## Sprite acceleration
  In the 1980's and the early 90's many home computers were built to do work rather than play games, therefore many
  of the video systems were built inorder to accomadate bisinuss users rather than games. Many games systems however, such
  as the Super Nintendo Entertainment system were built from the ground up inorder to play games. One of these features 
  were sprites shich were basically images that the programmer could move around.
  
  ![Sprite](image.png) 
  
  This approach made some games much faster. For example the texture of an enemy could be a sprite and multiple sprites
  could be moved on the screen without the programmer directly changing each pixel in the enemy. This makes the game much '
  faster as the computer does not have to tell the video chip what color every single pixel will have.
## 3d Accelerators
  http://fabiensanglard.net/3dfx_sst1/index.html
  Programmers always wanted to make 3d games as it allows more gameplay options to be explored than with 2d games. 3D games
  however require a large amount of computational power. In the early history 3d games used very simple graphics with 
  simple graphics consisting of lines or sometimes filled in polygons. These methods were very slow because programmer
  written code had to calculate where every single polygon fit on screen. in the mid 90's 3d accelerator cards started 
  to appear onto the consumer market. These devices used specalized hardware inorder to draw 3d graphics. These systems
  were much faster than traditional tecqniques and allowed much more interesting games to appear.
## General Purpose Compute
Initially 3d accelerators could only draw 3d graphics. Slowly the abilities of these graphics systems grew and could do more advanced tasks. In 2004 a new version of OpenGL a industry standard, used by programmers to write graphical applications. 
This version allowed the programmer to write programs that would run on the graphics chip. This allowed the programmer to 
leverage the graphics equipment for tasks that are not strictly related to puting pixels onto a screen. Graphical proccessers
can be much faster than traditional processers because they can do tasks in many small chunks at the same time rather then 
doing one task and moving onto the next task.

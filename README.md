# Super_Mario_Clone-Team_Red

To compile run the following code in powershell: -

g++ -c Animation.cpp ConvertSketch.cpp DrawMap.cpp Enemy.cpp Goomba.cpp Koopa.cpp Main.cpp MapCollision.cpp MapManager.cpp Mario.cpp Mushroom.cpp -I"Path\include" -DSFML_STATIC


To link all the .o files, run the following code in powershell:-

g++ Animation.o ConvertSketch.o DrawMap.o Enemy.o Goomba.o Koopa.o Main.o MapCollision.o MapManager.o Mario.o Mushroom.o -o RunGame -L"Path\lib" -lsfml-graphics-s -lsfml-window-s -lsfml-system-s -lopengl32 -lfreetype -lwinmm -lgdi32 -mwindows -lsfml-main

This will create an .exe file named "RunGame".
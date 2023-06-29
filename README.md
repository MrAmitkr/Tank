# Tanks

**This is a project I developed for summer project in college. when I first started learning C++ I utilized my knowledge and developed a very simple and fun game.
<br/>You can play this game with you friends. 
<br/>You can move using △ ◁ ▽ ▷ and shoot using 'K'. Your main goal is to destroy your opponent who can move using 'W', 'A', 'S', and 'D' and shoot you using 'C'.
<br/>Try it!**


## Some screenshots from our game
![Menu](https://github.com/magziim/Tanks/blob/main/Screenshots/menu.png)
![First map](https://github.com/magziim/Tanks/blob/main/Screenshots/bricks&box.png)
![Second map](https://github.com/magziim/Tanks/blob/main/Screenshots/bricks.png)

**You can also try to create your own map using .txt.
<br/>To do this, create a file and fill it with numbers.**

*numbers can be different, not only 1 and 0!*


```
// example
1 1 1 1 1 1 1 1 1 1 1 1 1
1 0 1 0 0 0 1 0 0 0 1 0 1
1 0 1 0 1 0 1 0 1 0 1 0 1
1 0 1 0 1 0 1 0 1 0 1 0 1
1 0 1 0 1 0 1 0 1 0 1 0 1
1 0 0 0 1 0 0 0 1 0 0 0 1
1 1 1 1 1 1 1 1 1 1 1 1 1

```
**To set map, go to "mainscene.cpp", line 43 and replace url:** 

```
map_creator.setFile("{url_to_my_map}\\my_map_name.txt");

```

![Third map](https://github.com/magziim/Tanks/blob/main/Screenshots/forest.png)
![GameMenu](https://github.com/magziim/Tanks/blob/main/Screenshots/gamemenu.png)

## How to play ?

**You need to compile the game using Qt Creator**

# CC-Tweaked-Farmer-Program
Minecraft 1.12.2 CC:Tweaked Configurable Farming Turtle Program
xmightymeatballx

the farm should be a square or rectangle, it can be an odd numbered size or even numbered size. i.e 4x4, 9x9, 10x10, 15x10 53x51. the turtle must occupy the bottom left or right corner of this square. which is configurable. he must be facing the length, and will work the width one row at a time.

the terminal will prompt you to create a config on the first go. for the vanilla minecraft crops (wheat, carrot, potato) you can simply type wheat, carrot, or potato
for crop type. for other crops that drop seeds when broken, you will need to enter exact ID's for the seed and crop. you can find those using F3 + H in-game and hovering
your mouse over the seed item. for the actual in-world growing crop getting the id is a little harder. im going to eventually add a code for the turtle to do that for you. the turtle can not right click to my knowledge, which means he can not harvest crops that offer a right click and do not drop seeds when broken.
the turtle uses the size of the farm to figure out the number of turns required to go up and down the rows, and so no matter the size he should know how to get back.

currently hes broken if the server restarts or chunk unloads, im working on fixing that without using the GPS api

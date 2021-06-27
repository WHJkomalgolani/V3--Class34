# C34:
Youtube link:
https://youtu.be/phGSX8gCPcs

https://youtu.be/Hq7KGsfkq5I

Note: There is a bug in the code. Player should always first opt for blower star and then for normal star.
So we have modified the pdf code as below(line 177 to line 191):

if (collide(fruit, star, 20) == true) { star.visible = false; star_display.changeAnimation("one"); }

if (collide(fruit, star2, 40) == true && star.visible === true) { star2.visible = false; star_display.changeAnimation("one"); } else if (collide(fruit, star2, 20) == true && star.visible === false) { star_display.changeAnimation("two"); }

To do list:
c34 - stars and scores



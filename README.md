# C34:
Youtube link:
https://youtu.be/phGSX8gCPcs

Note: There is a bug in the code. Player should always first opt for blower star and then for normal star. So we have modified the pdf code as below:

if (collide(fruit, star, 20) == true) { star.visible = false; star_display.changeAnimation("one"); }

if (collide(fruit, star2, 40) == true && star.visible === true) { star2.visible = false; star_display.changeAnimation("one"); } else if (collide(fruit, star2, 20) == true && star.visible === false) { star_display.changeAnimation("two"); }

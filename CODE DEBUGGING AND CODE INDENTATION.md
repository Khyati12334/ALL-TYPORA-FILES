



# CODE DEBUGGING AND CODE INDENTATION

Giving space line by line in the code to reduce the confusion is known as CODE INDENTATION.

Code Indentation— Leave a space after every meaningful line of code.

Bug means ERROR. DEBUGGING means correcting the error.

Learn to use console.log(). The P5 editor has a console window where we can log any message while the program is running. We do this using console.log().

INVISIBLE OBJECTS - Objects which are not visible.

Code for INVISIBLE GROUND-

if (ground.x < 0) 
  {
  ground.x = ground.width / 2;
  }

To make the ground invisible-

 invisibleGround= createSprite(200,190,400,10);

  invisibleGround.visible=false;
}
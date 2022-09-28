# javaScript-Programs
This program use for adding some audio clips to keyboard keys.when we touch the selected keys it will play audios which we are assigning them..
In this we create a html program using some div,audios to playing keyboardtones.
In this we also create a css program to make some styles of Html program.
In Html program we create an image "flower" to place on the screen look beautiful.
After that we create data-keys like 66,84,69,78,90.those are represented as B,T,E,N,Z.
For these keys we create classes because we can style them easily using "Class" names.after "data-keys" we create KBD(keyboard Input Elemet) to declare the Alphabet.
And then we using span to describe the name of audioClip.And assign some class name called "Sound".Sound classname is used for style them easily.
After that we assign some audioclips to the data-keys.
In Styles.css we style the classes.We assign height,width to image.Keys class we assign width,height.And align-Items in "center".justify-Content in"center".display:'flex' is used for align data sideby side.
We assign key classes ,border,border-radius,margin,font-size,padding,width.''trasition is used for transform the data in some assigned time''.we assign some color,background,text-align is used for add the data in center of box.text-shadow is the shadow of the data.
Playing class is used for play the assigned audioclips of data.In this Transform is used for transformation of data calculate with scale.On tranformation we assign some border-colorand box-shadow.
we assign kbd some display,font-size.To Sound Class we assign font-size,text-tranform,letter-spacing,color.


To know the transformation of data audio we create audio,key constants.In these we check the transionend data.
if the audio is assignedd it will play,otherwise it not respond.We add playing message to class like key"playing".
We create a function Called "removeTransition"to check the transform is done or not.after tranform we eleminate the playing message.
playSound function is active when the right button is pressed.

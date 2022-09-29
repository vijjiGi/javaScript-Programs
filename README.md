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


window.addEventListener('keydown',function(e);.In this line we know the keyboard event.If we want to watch the result we give a statement like"console.log(e)".In this e is describing function result like keyboardEvent.
if we want to see the keyCode we do like "console.log(e.keyCode);".
Using attribute selector we know the audio elements.we using querselector to know the audio attributes and watch using "console.log(audio)".
if the selecting attribute is not audible it will give "null".
we can check if it is not audible it will return or if it is audible it will play usig "audio.play();".In this there is a gap between audios which are we play continuously.
To avoid that we can manage the time using "audio.currentTime=0".Then it will play continuously. 
we can check the support key of the audio using key with attribute selector and console them..
we add playing class when the audios are playing it will give some other functions or styles like scale,border-color,box shadow like these.And it add to key class when it playing it will show key+playing.
But here we cant dissapear the classEvent "playing" automatically.Here we can use a function timeOut but not work properly.
Thats why we can use a quick event like "transitionend" to know the transmission.to know all the transmition of attributes we loop them and check them.
After checking of transmition, for automatically disapper of classEvent we use a function called removeTransition.(If u want In this function if propertyNaame "tranform" is done we print the propertyName "transform" using "e.prpertyName".
In this statement we can use "this" keyword to describe "key" class.After transitionend we can remove the classList using "remove(playing)".
That will delete the classList next to the key.we will create the function to classList "keydown" called "playSound".It looks the good data after creating function.Then the keydown ClassList we can place on last line. 

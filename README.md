# MonoGame-SpriteFont-HardEncoder-To-Class
This rep is a single class with nested classes that facilitate the abilty to turn a spritefont into a loadable cs file.

So this class you give it a sprite font and call the write method.

What you get is a text file.
You copy paste that text file into a class in your monogame project or make one with the same name.
The text file is basically a ready made copy paste class file.

There is a method that you call that essentially returns a Spritefont from that class.
So if you add that generated class to any project no texture is needed.
No call to content load is needed you don't have to load anything.
Is it useful ?.. well i made it as a default spritefont essentially a part of monogame.

Basically you can copy paste this into any monogame project which is the resulting output of one i already encoded.
To have simple premade spritefont.
.

https://github.com/willmotil/MonoGame-SpriteFont-HardEncoder-To-Class/blob/master/Example/ExampleOutput.cs

.
Basically in loadcontent or were ever call.

SpriteFont font = new HardCodedSpriteFont().GetFont(GraphicsDevice);

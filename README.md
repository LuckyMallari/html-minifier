# html-minifier
A simple HTML minifier for ESP/microcontrollers

For embedded systems where memory is crucial, you'd want to save as much as possible. Even unnecessary spaces should be removed because every bit counts! What this code does is take your HTML code and minimizes it using regular expression. It DOES not minify the code like others do, it will simply remove unnecessary characters.

I use this primarily for ESP when a simple html code will be served using a lightweight webserver. 

##### Example/Demo
Minifying the minifyer itself, we save 30% !

![Demo](https://raw.githubusercontent.com/LuckyMallari/html-minifier/master/minifierdemo.png)
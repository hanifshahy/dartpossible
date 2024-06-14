# Dart is a professional wrapper for JavaScript

In this Section we will show you how to compile dart code to JavaScript.

## Requirement

1. Dart 
2. Node js

## Getting started

1. Create a directory ( mkdir dart_to_js)
2. Change the directory to one you have made ( cd dart_to_js)
3. Create a .dart file ( touch main.dart)
4. Open it with your favorite text editor (code ./dart_to_js)
5. Simply add the following code in it.

void main(){
  print('Hello, World!');
}

6. Run this command ( dart compile js -o main.js)
7. Above command will generate a JavaScript file (main.js)
8. Now lets run both by following commands
   1. dart run main.dart
   2. node main.js
9.  Finaly both files must print the same message (Hello, World!) .


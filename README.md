# Simple-Web-Server-using-go

Go is an open source programming language supported by Google
Easy to learn and get started with for scripting purposes and alongside for networking.

In this simple web server we have imported three packages - 
  1. fmt - fmt stands for the Format package. This package allows to format basic strings, values, or anything and print them or collect user input from the console, or            write into a file using a writer or even print customized fancy error messages. This package is all about formatting input and output.
  2. log - Package log implements a simple logging package.
  3. net - Package http provides HTTP client and server implementations. 
           Get, Head, Post, and PostForm make HTTP (or HTTPS) requests
           
           
           
           
 ![image](https://user-images.githubusercontent.com/68628209/180711708-01267c8d-36e0-4ebc-9792-0de3322f1039.png)
 
 The above diagram represents the three routes from the server file
 
 1. / route - This file will simply open the index.html file
 2. /hello route - This route will execute the hello function which is written in the code.
 3. /form route - This will take us to a form, where we will be taking the input of the user's name and user's address and after that it will execute the form function, which will display the details that the user has filled in the form.

These routes are written inside the "func main()" file.

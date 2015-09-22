Title: How To Install A MineCraft Client On Ubuntu
Date: 2015-09-22 10:20
Catergory: HowTo

Good day guys! I am Jake and I am going to tell you how you install Minecraft on an Ubuntu desktop machine.


Before we can venture onto installing Minecraft on Ubuntu Desktop, We must install a Java Runtime Enviroment. For the easiest way to install Java, go to Software Center and install OpenJDK.

or run the following commands in terminal 

```sh
$ apt-get update
$ apt-get install default-jdk 
```

Now follow these steps to install the Minecraft Client. 

##Step One:

Go to the terminal.

##Step Two:

Go to http://minecraft.net/download and get the .jar file from the official website and put it in the desktop

or run the following from the terminal

```sh
$ cd ~/Desktop
$ wget https://s3.amazonaws.com/Minecraft.Download/launcher/Minecraft.jar
```
##Step Three: 

Go to the terminal again

Run this following commands

```
$ cd ~/Desktop
```
This will make sure you are in the directory of where the Minecraft.jar is.
Then run this following

```
java -jar Minecraft.jar
```

And it should open up the launcher and you should be able to play!

Enjoy crafting!

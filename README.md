# Using the Learn IDE (Integrated Development Environment)

The Learn Integrated Development Environment (IDE) is what you'll be using to write code and submit your labs on Learn. Let's take a closer look at what it is and how it works.

We created the Learn IDE based off of GitHub's very popular text editor, Atom. We've taken advantage of its highly configurable design by optimizing it to solve labs on Learn in two key ways. (1) We've configured a server in the cloud with all the tools and packages you need to build software, as well as the files you'll work on while solving Learn Labs. (2) We've given you access to that server via a Terminal window within the app.

So you can think of the Learn IDE as a powerful text editor that gives you handy access to a fully-equipped development environment in the cloud. And since you're connected to that server in the cloud, the files and folders you're able to see in the Learn IDE are those that exist on that server, rather than the files on your computer. That may sound confusing, but you'll see that in practice, you'll have access to all of the files you need for Learn and it will feel very natural.

## What are the Components of the IDE?

Let's spend a minute studying the Learn IDE user interface. You'll notice that it's composed of three sections: (1) a file browser (2) a text editor and (3) the console which you'll see in the image below.

![IDE](https://s3.amazonaws.com/learn-verified/Screen+Shot+2016-04-15+at+3.48.17+PM.png)

### IDE File Browser

![IDEFileBrowser](https://s3.amazonaws.com/learn-verified/ILE-BrowserFile.png)

The left side of your IDE application houses a simple file browser. It works just like a file browser on any computer: you can navigate a tree of folders and files to find the file you're looking for. Opening a file will open its contents in the text editor on the right. This is often the most convenient way to see the structure of a file tree and find a file quickly.

Important note: If you need to add any files into the Learn IDE (pictures, or other files that did not come with the lab), you can add them by right click (or option + click on a Mac) on the folder you would like to add them to and selecting Import File from the menu. 

Reminder: the files you can see and access here on your local computer and are in synced to the server you're connected to via the Learn IDE. The files you see when you type `ls` are on the server (and assuming you're only using one computer, these should be the same lists of files).

### IDE Text Editor

![IDETextEditor](https://s3.amazonaws.com/learn-verified/ILE-TextEditor.png)

The text editor is the heart of the IDE. It's where you'll write code, and where you'll be spending most of your time. Again, we built the IDE on top of Atom, a free open-source text editor by GitHub. One of the nifty things about text editors that have been optimized for programming is that as you type, your code will highlight in ways that make it easier to discern the structure of your program. You'll notice this when you start writing your own code.  

When you click on a file in your file browser, it will open up in the text editor portion of the IDE and you can go ahead and edit right there.

### IDE Terminal

![IDETerminal](https://s3.amazonaws.com/learn-verified/ILE-Console.png)

While the upper part of the screen is where you write code, the lower part of the screen is the terminal where you'll be typing in commands to navigate files and folders.

Reminder: Whenever you save your files, they are synced to the server. Once they're on the server, we can run through the terminal here.

## Important note about connectivity

You need an Internet connection in order to use the Learn IDE. You can edit code in your text editor when you're offline, but you will only be able to save it when you re-establish a connection.

Hint: If you see the word "Learn" in green letters below your Terminal, you're connected.  

![IDE Connected](https://s3.amazonaws.com/learn-verified/IDEConnected.png)

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/your-integrated-development-environment'>Your Integrated Development Environment</a> on Learn.co and start learning to code for free.</p>

<p class='util--hide'>View <a href='https://learn.co/lessons/your-integrated-development-environment'>The Learn IDE</a> on Learn.co and start learning to code for free.</p>

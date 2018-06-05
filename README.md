# Using the Learn IDE (Integrated Development Environment)

You are probably familiar with using an application like Microsoft Office, Open Office, or Google Docs to create things like documents and spreadsheets. You've probably also used applications like Safari, Chrome, or Internet Explorer that allow you to access and interact with the internet. What kind of program allows us to write code?

There are many different applications that allow you to both see and edit code. These are called text editors. One advantage of some text editors is they allow you to customize them in a highly personalized manner. There are different plug-ins that you can download to allow you to do everything from simply changing text style and color to auto-formatting and auto-complete. Some text editors you might have heard of include Vi, Atom, Sublime, Notepad, and Visual Studio Code.

The Learn Integrated Development Environment (IDE) is a web-based version of GitHub's text editor, Atom, plus a (terminal / shell / command prompt) — all in one. When you launch Learn Learn IDE you'll see a "file tree" and a text editing space. Those are provided by Atom. The terminal at the bottom is something we've added to help you test and interact with your code. You can think of the Learn IDE as a powerful text editor that gives you handy access to a fully-equipped development environment in the cloud. And since you're connected to that server in the cloud, the files and folders you're able to see in the Learn IDE are those that exist on that server, rather than the files on your computer. That may sound confusing, but you'll see that in practice, you'll have access to all of the files you need for Learn and it will feel very natural.

## What are the Components of the IDE?

Let's spend a minute studying the Learn IDE user interface. You'll notice that it's composed of three sections: (1) a file browser (2) a text editor and (3) the terminal which you'll see in the image below.

![IDE](https://s3.amazonaws.com/learn-verified/Screen+Shot+2016-04-15+at+3.48.17+PM.png)

### IDE File Browser

![IDEFileBrowser](https://s3.amazonaws.com/learn-verified/ILE-BrowserFile.png)

The left side of your IDE application houses a simple file browser. It works just like a file browser on any computer: you can navigate a tree of folders and files to find the file you're looking for. Opening a file will open its contents in the text editor on the right. This is often the most convenient way to see the structure of a file tree and find a file quickly. You can open a file by double-clicking the file name.

Reminder: the files you can see and access here are those that exist on the server you're connected to via the Learn IDE, not those on your local computer.

### IDE Text Editor

![IDETextEditor](https://s3.amazonaws.com/learn-verified/ILE-TextEditor.png)

The text editor is the heart of the IDE. It's where you'll write code, and where you'll be spending most of your time. Again, we built the IDE on top of Atom, a free open-source text editor by GitHub. One of the nifty things about text editors that have been optimized for programming is that as you type, your code will highlight in ways that make it easier to discern the structure of your program. You'll notice this when you start writing your own code.  

When you click on a file in your file browser, it will open up in the text editor portion of the IDE and you can go ahead and edit right there.

Hint: Don't forget to save your work often so you don't lose it! A good rule of thumb is to save and commit your code every 3-5 lines. You will learn more about committing your code to GitHub in a few lessons, but for now just save your work by going to File -> Save, command-s (Mac), or control-s (Windows). If your tests are failing on a lab, and you're not sure why, make sure you've saved your code _before_ running your tests!

### IDE terminal

![IDETerminal](https://s3.amazonaws.com/learn-verified/ILE-Console.png)

While the upper part of the screen is where you write code, the lower part of the screen is the terminal where you'll be typing in commands to navigate files and folders.

Reminder: again, just like the file tree on the left, this terminal gives you access to the files and folders on our server, and not the files and folders on your local computer.

Hint: Try using `pwd` to see your working directory, and using `cd` and `cd ..` to navigate between folders. You can also use `ls` here to see your files and folders in your working directory. Practicing your new commands is a great way to ensure you remember them.


## Important note about connectivity

You need an Internet connection in order to use the Learn IDE. You can edit code in your text editor when you're offline, but you will only be able to save it when you re-establish a connection.

Hint: If you see the word "Learn" in green letters below your Terminal, you're connected.  

![IDE Connected](https://s3.amazonaws.com/learn-verified/IDEConnected.png)

## Key Terms
- Text editor
- IDE
- File Browser
- Terminal



<p class='util--hide'>View <a href='https://learn.co/lessons/your-integrated-development-environment'>The Learn IDE</a> on Learn.co and start learning to code for free.</p>

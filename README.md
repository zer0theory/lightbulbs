# lightbulbs

> A quick way to jot down an idea before it escapes.

Ever have a great idea and you know you have to write it down quickly or you'll likely forget? This is the tool for you!
Just run this command to open your favorite text editor to write down and safe a note. This creates a folder in your home directory named **Lightbulbs** 

---


## Use

```sh
git clone https://github.com/zer0theory/lightbulbs.git
cd lightbulbs/
./lightbulb
```

By default the text editor is set to [neovim](https://neovim.io/) If you wish to use another text editor, modify the script changing the instance of **nvim** to whichever editor you prefer.


## Custom Lightbulb Directory

Edit the lightbulb file with your favorite text or code editor and change the directory to where you wish.
If you use [Obsidian](https://obsidian.md) you can set the directory within that directory structure and Obsidian will recognize the folder and files instantly.


## Move to Path

To make life easier on yourself you can move the lightbulb file to your path.

```sh
cp lightbulb /usr/local/bin/
```



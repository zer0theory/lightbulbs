# lightbulbs

> A quick way to jot down an idea before it escapes.

![brilliant!](brilliant.png)

Ever have a great idea and you know you have to write it down quickly or you'll likely forget? This is the tool for you!
Just run this command to open your favorite text editor to write down and save a markdown note. 

---

## Use

```sh
git clone https://github.com/zer0theory/lightbulbs.git
cd lightbulbs/
./lightbulb
```
This will create the ~/Lightbulbs directory if it doesn't exist then create your first note as well as enter it with the text editor. Simply Write down your million dollar idea and save the file. This creates files starting at lightbulb001.md and increases in number as you create new ideas.

By default the text editor is set to [neovim](https://neovim.io/) If you wish to use another text editor, modify the script changing the instance of **nvim** to whichever editor you prefer.


## Custom Lightbulb Directory

Edit the lightbulb file and change the directory to where you wish.

If you use [Obsidian](https://obsidian.md), you can set the directory within your Obsidian notes directory and Obsidian will recognize the folder and files instantly.

## Move lightbulb to Path

To make life easier on yourself you can move the lightbulb file to your path.

```sh
cp lightbulb /usr/local/bin/
```

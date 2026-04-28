# lightbulbs

## ***“Your mind is for having ideas, not holding them.”* – David Allen**


> A quick way to capture an idea before it escapes.

![brilliant!](brilliant.png)


## Ideas

Ever have a great idea and you know you have to get it in writing quickly or you'll likely forget? This is the tool for you!
Just run this command in a terminal to open your favorite text editor to capture it to a markdown file.


## Use

```sh
git clone https://github.com/zer0theory/lightbulbs.git
cd lightbulbs/

```

Then run

```sh
./lightbulb
```

By default, this will create the ~/Lightbulbs directory. Then creates your first lightbulb note and enters it with your text editor. Simply write down your million dollar idea and save the file. This creates files starting at lightbulb001.md and increases in number as you create new ideas.

Use `lightbulb -h` to see all options.

By default, it uses the editor set at environment variable $EDITOR. If this isn't set, it will default to neovim [neovim](https://neovim.io/) then vim. If you wish to use another text editor, modify the script changing the instance of **nvim** to whichever editor you prefer or set your $EDITOR variable.


## Custom Lightbulb Directory

Edit the lightbulb script file and change the directory to where you wish.

If you use [Obsidian](https://obsidian.md), you can set the directory within your Obsidian notes directory and Obsidian will recognize the folder and files instantly!

## Move lightbulb to Path

To make life easier on yourself you can make a symlink of the script to your path.

```bash
sudo ln -s "$(realpath ./lightbulb)" /usr/local/bin/lightbulb
```

Or...

```bash
ln -s "$(realpath ./lightbulb)" ~/.local/bin/lightbulb
```
```


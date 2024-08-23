Since our first main topic will be learning to use the Linux shell, and
since we are going to use *markdown* quite a bit, let's use a tool
known as `pandoc` to convert this markdown document to html.

**IMPORTANT:** Pandoc is already installed on the pcda virtual machine.

[http://pandoc.org/index.html](http://pandoc.org/index.html)

[http://pandoc.org/getting-started.html](http://pandoc.org/getting-started.html)

Start by opening up a bash shell. You can do by using CTRL-ALT-t or use the blue start button and select System Tools | QTerminal. Then at the command prompt run the following pandoc command.

**IMPORTANT:** The '$' below is **NOT** part of the command. It is representing the bash shell prompt. 

    $ pandoc PP1_IntroToPCDA.md -f markdown -t html -s -o PP1_IntroToPCDA.html
    
You can certainly type in the whole command, or you can copy and paste it into the bash shell. Just right click at the command prompt and find the obvious way to paste in the command. Note what
the keyboard shortcut is for pasting into a bash shell (it's NOT CTRL-v).

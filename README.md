# About my template:

## How to use?
+ The way I have it set up (with vim obviously), is that whenever I open a new .tex file, it starts with that source code, if you want to know how to do this its pretty simple, just download my template or write your own, place it somewhere that will always be on your computer and then go to your vimrc file. You have to add just one line:
```
autocmd BufNewFile *.tex 0r ~/Folder_or_path_to_your_template_file/template.tex
```

## Why is it like that?
+ Well, actually the source code is not very clean or compact, but the final result has all the features I like, but feel free to modify it or do your own one.

## More tips:
+ I actually have a setup in which I am editing a .tex file in vim and just hit some keys and compile and show the .pdf automatically so thats fast, you just have to map the key combo to a compiling script. That compiling script should take the name of the file and pass it to pdflatex. A note here: I had to use the ```-interaction=nonstopmode``` to get it working correctly :)

## Any suggestions?
+ Feel free to pr


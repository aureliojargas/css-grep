# The grep-friendly CSS reference

1) Download the text file to your home folder.

```console
$ curl -o ~/css.txt https://raw.githubusercontent.com/aureliojargas/css-grep/master/css-grep.txt
```

2) Create a nice Bash alias.


```console
$ alias css='cat ~/css.txt | grep --color=auto -i '
```

3) Enjoy your instant CSS reference with the new `css` command.

```console
$ css italic
font-style            : normal, italic, oblique

$ css bold
font-weight           : normal, bold, bolder, lighter
font                  : bold 12pt Arial

$ css back
background-color      : transparent, white, #FFF, #FFFFFF
background-image      : none, url(file.jpg)
background-repeat     : repeat, repeat-x, repeat-y, no-repeat
background-attachment : scroll, fixed
background-position   : top, center, bottom, left, center, right
background            : white url(file.jpg) no-repeat top left
```

Tip: Save the alias command (step 2) to your `~/.bashrc` to make it permanent.


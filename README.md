# PrettierIgnore

While I'm not against uniform code ethics across projects... one of the best known code reformatters, Prettier, is just **way too opinionated**!

## How to ignore stuff
Prettier's own documentation tells you how to ignore certain parts within certain files... or how to ignore whole files with a .prettierignore file. Check their docs for more details, over at https://prettier.io/docs/en/ignore.html

## Why include a .prettierignore file?
You yourself may not have Prettier installed, but other coders may still use it. If you don't like Prettier to mess up any of your web files, you can use the .prettierignore file which I have included in this repo. 

The file tells Prettier to ignore all know web formats, a lot of common files, folders and other stuff.

## Why is this file soo big?
I read online (source lost) that Prettier sometimes ignores its own /* within the .prettierignore file. To force them to really ignore specific file extensions, I made a list of all known web formats, across several developer systems. This also includes server sided formats. 

Thats why the file is 300 lines and more.

## Help out!
If you know formats that are missing, feel free to add them, or contact me, to add them to this repo.

**Victor van der Put**<br>
[@MakePixelsWork](https://github.com/MakePixelsWork)

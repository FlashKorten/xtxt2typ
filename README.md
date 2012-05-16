xtxt2typ
========

If you run xtxt2typ without any parameters you will get some help on the different possible parameters.
The descriptions are quite terse - but nothing too complex - play with them to get to know them.

One thing you should do with the text you want to type:

 - Put the title of the text in the first line
 - Start every line containing a title of a new chapter with a marking (the default is `__chapter__`)

One pitfall: if the lines are too long in the textfile gtypist will not work with the result.
If this happens to you send the textfile through a filter like fmt or something comparable...

`xtxt2typ INTERESTING_TEXT.xtxt`

converts the textfile to a gtypist lesson file, which you can use like this:

`gtypist INTERESTING_TEXT.typ`

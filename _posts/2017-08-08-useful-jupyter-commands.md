---
layout: post
title:  "Jupyter cheatsheet"
categories: posts
---

This is an overview of the essential Jupyter hacks that we've covered in the course. If you have one that you wish to share, make a pull request in our course page's [GitHub repo](https://github.com/abjer/sds).

*Relevant Jupyter keyboard short cuts*

Editing and executing cells
- enter edit mode: click inside the cell or press `ENTR`
- exit edit mode: click outside cell or press `ESC`.
- executing code within a cell is `SHFT`+`ENTR` or `CTRL`+`ENTR` (not same!)

Adding removing cells (command mode only)
- delete a cell:`d`,`d` (press `d` twice)
- add cell: `a` above, `b` below

Converting between markdown and code (command mode only)
- as markdown: `m`
- as code: `y`

See all Jupyter keyboard shortcuts in menu (top): `Help > Keyboard Shortcuts`, or press `H` in command mode.

*Autocompletion*

Within Jupyter the `TAB` command will autocomplete your code. This can also be used to see which methods are available for a given object.

*Plotting*

Using the syntax `%matplotlib inline` allows you to make figures within Jupyter notebook.

*Function description*

Execute a cell with `?fct` will give you information about the function `fct`. Note this command also work on objects' methods.

# FuncDocr

A brackets extension to generate JS/PHPDocs for your functions.

## How to Use
* Open a JS or PHP file
* set your cursor on a function declaration
	* `function cool(stuff)`
* Use the ShortCut `Ctrl-Alt-D` (Win) or `Ctrl-Shift-D` (Mac) to start the documentation


The extension will provide a function documentation:
![](https://cloud.githubusercontent.com/assets/4931746/4141317/f9303404-33ac-11e4-8e3c-c72925b4e550.gif)

`[[Description]]` will be selected so you can start to type. To jump to the next `[[tag]]` you can use `Tab` or jump to the last with `Shift-Tab`. The indenting updates on a tab jump (live indenting).

You will get hints for the `[[Type]]` tag.

![Type hints](https://cloud.githubusercontent.com/assets/4931746/3998983/b3eba9ba-294c-11e4-988b-4330735635fd.png)

Have fun and stay tuned!

## v0.5.0
+ It's possible to generate the doc block with `/**` + Enter. You only need to type `/**` in the line above the function declaration and use enter to start the documentation.

## v0.4.0
+ The padding for correct indentation updates on a tab jump

## v0.3.0
+ It's possible to update a doc block if you add a parameter or delete one (you need to use the shortcut again)

## v0.2.0
+ You get the tag `@returns` if the function returns a value
+ The `[[Type]]` is recognized if possible.


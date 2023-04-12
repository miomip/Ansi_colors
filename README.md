# Ansi colors for the terminal
***
* Ansi is a set of color codes when used in terminals like the vscode terminal display a color on the text it's used on.
* To use the ansi color codes write it in a string like this (Example in kotlin) println("\u001b[32m") and to apply text write it like this println("\u001b[32m" + "Hello World!")
> #### The set of colors provided are mostly all the colors there is, if you need a color that isn't in the Color.kt file try running the main.kt file and look at those colors

#### NOTE: Most languages support Ansi, but not all. The C progarmming language doesn't support Ansi and will only return a error message when ran.

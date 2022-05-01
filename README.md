# Mklicense
![image](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-1.png)

**mklicense** (*Make License*) is a simple script to spit out the contents of software licenses for all those lovely `LICENSE` files in your git repos.

This script does not necessarily support every license out there. Any Help you'd like to provide in doing so is **more** than welcome.
## Q&A

### Why Does This Exist?
Have you ever gotten tired of copy/pasting the text of a Software License into `LICENSE` when working off of GitHub on something?
That's why.

### My Prefered License Isn't Supported. What should I do?
Fork, edit, and submit a Pull Request.

### In Order To Add My License, I Need More Info Than "$COPYRIGHT", "$EMAIL", "$YEAR", etc.
In your fork, *add* support for that extra variable you need.

Just be sure to use **ALL CAPS** to follow the existing formatting and don't forget to update the `help_msg()` function to show it.


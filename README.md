# progressbar
shell script to generate a dynamic progressbar based on the current terminal/gnu screen/tty instance

# Usage
run `progressbar $percentage $character` for example `progressbar 50 #` will fill the bar up halfway with hashtags.  
please make user to only evere put one character as the second argument, otherwise the width of the progressbar is wider tha the width of the terminal.  
The default character is "#" so `progressbar 50` will also fill the bar up halfway with hashtags.

![Screenshot][]

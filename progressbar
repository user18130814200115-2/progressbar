#!/bin/sh

char="#"
[ -n "$2" ] && char="$2"

width=$(($(tput cols)-2))
echo -n "["
for ((n=0;n<$(("$1*$width/100"));n++)); do
	echo -n "$char"
done

for ((n=0;n<$(("$width-$1*$width/100"));n++));do
	echo -n " "
done
echo "]"

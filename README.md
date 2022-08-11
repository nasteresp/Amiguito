# hello-world
Hello World repository for Git tutorial
This is an example repository for the Git tutoial on https://www.w3schools.com

This repository is built step by step in the tutorial.

Ahora incluye distintos pasos.
News changes

ex03

find . | wc -l

ex06

ls -l | awk ' NR % 2 == 0 '

ex07
cat etc/passwd | sed '/^#/d' | awk '{ if(NR % 2 == 0) print }' | cut -d ":" -f1 | rev | sort | awk ' 'NR==$FT_LINE1,NR==$FT_LINE2' { print }' | sed 's/$/,/g' | tr "\n" " " | sed 's/\(.*\), /\1./'

ex08

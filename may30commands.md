    1  curl http://archive.org/stream/diplomaticcorre33statgoog/diplomaticcorre33statgoog_djvu.txt > texas.txt
    2  nano texas.txt
    3  grep '\bto\b' texas.txt
    4  sed -r -i.bak 's/(.+\bto\b.+)/~\1/g' texas.txt
    5  ls
    6  nano texas.txt
    7  grep '~' texas.txt > index.txt
    8  nano texas.txt
    9  sed -r -i.bak 's(,)( [0-9]{4})(.+)/\2/g' index.txt
   10  nano index.txt
   11  sed -r -i.bak 's/(,)( [0-9]{4})(.+)/\2/g' index.txt
   12  nano index.txt
   13  sed -r -i.bak 's/~//g' index.txt
   14  nano index.txt
   15  sed -r -i.bak 's/(\b to \b)/,/g' index.txt
   16  nano index.txt
   17  history
   18  history > may30commands.md

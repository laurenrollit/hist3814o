    1  mkdir wget-activehistory
    2  cd cd wget-activehistory
    3  cd wget-activehistory
    4  wget http://activehistory.ca/papers/
    5  wget -r --no-parent -w 2 --limit-rate=20k http://activehistory.ca/papers/
    6  history
    7  history > activehistory.md

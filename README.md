# Easy bash loops
A small script for easily creating yes/no bash loops for use in scripts. You can

- Enter a question
- state what happens if yes or no
- save the file to your working directory (automatic renaming if there are duplicates)
- save the file to a custom directory (no matter if ending with "/" or not)
- copy the loop to your clipboard (Wayland only)

![Screenshot](https://github.com/trytomakeyouprivate/easy-bash-loops/blob/main/bash-loops.png)

![Screenshot 2](https://github.com/trytomakeyouprivate/easy-bash-loops/blob/main/bash-loop-2.png)

![Screenshot 3](https://github.com/trytomakeyouprivate/easy-bash-loops/blob/main/stallmanloop.png)

I fixed the code completely. It works very well now.

Dependencies:
- bash
- cat
- wl-clip (change it to xclip if you want)
- read
- printf (only for header)

## Install

```
wget https://github.com/trytomakeyouprivate/easy-bash-loops/raw/main/create-loop -p ~/.local/bin
chmod +x ~/.local/bin/create-loop
```


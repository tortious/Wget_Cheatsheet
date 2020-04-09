# Wget_Cheatsheet
my personal cheetsheet of useful wget commands

### Download a single file
wget [URL]

### Resume download (*e.g.* if it gets interrupted)
wget -c [URL]

### Download file but use a different File Name
$ wget -O [file-name] [URL]

### Redirect Wget to a Log File
$ wget -o [log-filename] [URL]

cat abc.log - This shows the log

### Download Files in Background
wget -b [URL]

### Modifying the look of the progress meter in terminal
wget --progress=dot [URL]

wget -–progress=[type]:[parameter]

wget -–progress=dot:binary [URL]

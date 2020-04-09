### Save using custom name (notice the .xxx remains the same when naming)
wget -O myFile.txt domain.com/file.txt

### Download Single File using FTP
wget --ftp-user=FTP_USERNAME --ftp-password='FTP_PASSWORD' ftp://URL/PATH_TO_FILE/FILE_NAME

### Download File in Background
wget -bq domain.com/file.txt

### Download Full Hmtl of Website
wget -m http://domain.com

### Example Downloading a Directory (taken from reddit/r/opendirectories comment)
wget -r -c -np "213.32.1.25/House%20Of%20Gord/" 
wget -r -c -np "213.32.1.25/Gord/"

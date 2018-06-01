> This script will work only with Python 2.7

### Overview

This script is use to upload regular files and large files to s3 bucket. Based on [Data Reguge](https://github.com/datarefuge) Synopsis, this script enables you to upload objects that are larger than 5 GB in size.

### Usage

`python s3upload.py bucket-name path-to-file` 

### Requirement 

Make sure you have install boto using 

`pip install boto`

For Windows, you also need to install FileChunkIO using

`pip install filechunkio`

### Setup

1. Copy `s3upload-mac.py` to your local if you're using Mac. 

2. Copy `s3upload-win.py` to your local if you're using Windows.

3. Rename it to `s3upload.py`, add your AWS access key in the script:

   ```python
   AWS_ACCESS_KEY_ID = ' '
   AWS_SECRET_ACCESS_KEY = ' '
   ```

### Thanks to

http://codeinpython.blogspot.com/2015/08/s3-upload-large-files-to-amazon-using.html

and [data Refuge](https://github.com/datarefuge/s3uploader)

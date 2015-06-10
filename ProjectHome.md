# No Longer Working #
This script is NO LONGER WORKING and is discontinued.

# ~~PHP Youtube Downloader~~ #
~~PHP Youtube Downloader is a simple PHP script to download video from Youtube.com~~


## Requirements ##
PHP with CURL

## Change Log ##
  * November 13, 2008 (0.5) Read HTML from Youtube page to get T string.
  * April 15, 2008 (0.4) Shot the SWF and read the header and let the T string remain
  * March 3, 2008 (0.3) Shot the SWF and read the header
  * April 5, 2007 (0.1) Read HTML and parse the string


## Usage ##
```
<?php
require_once('youtube.lib.php');
$download_link = get_youtube('http://www.youtube.com/watch?v=SAQZ0BDXn48'); 

// we will have array here, index 0 is the video ID and index 1 is the download link.
echo $download_link[1];
?>
```
Make sure to ALWAYS add WWW in the youtube links.


## Ready Script ##
If you're looking for a script that is ready to use, download http://php-youtube-downloader.googlecode.com/files/youtube_downloader.zip and read the README file inside the package.


## Disclaimer ##
You use it at your own risk.
You can ask me question about this script but you shouldn't  ask me for any damaged computer caused by this script.

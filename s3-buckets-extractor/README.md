# s3-buckets-extractor
PHP tool to extract datas from Amazon S3 bucket  
Note that this is an automated tool, manual check is still required.  

```
Usage: php s3-buckets-extractor.php [OPTIONS] -b <bucket name>

Options:
	-b	set bucket name (required)
	-d	set destination directory
	-g	grab the directories/files
	-h	print this help
	-i	extensions to ignore (default=bmp;gif;jpg;jpeg;svg)
	-v	set verbosity: 0=none, 1=only readable, 2=all (default=2)

Examples:
	php s3-buckets-extractor.php -b test-test -g -d /tmp
	php s3-buckets-extractor.php -b test-test -v 1 -i txt;ttf;woff
```

I don't believe in license.  
You can do want you want with this program.  

![s3 buckets extractor example]
(https://raw.githubusercontent.com/gwen001/s3-buckets-extractor/master/example-ex.png)

![s3 buckets bruteforcer example]
(https://raw.githubusercontent.com/gwen001/s3-buckets-extractor/master/example-bf.png)

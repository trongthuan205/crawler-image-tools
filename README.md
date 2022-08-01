## Introduction
Crawled Images From Search Engine Tool can download images and URLs from Google and Flickr. In particular, images can be downloaded through keywords.

## Step 1: Get URL's Images

**1. Google:**

-   Search your images and start scrolling to the end.
-   Press F12 to access the console.
-   Copy + paste the function in the `get_google_urls.js` file into the console.

**2. Flickr:**

-   Example: `python get_flickr_urls.py -o 'images' -k 'cat'`

```
usage: get_flickr_urls.py [-h] -o OUT -k KEYWORD [-p PER] [-m MAX]

optional arguments:
  -h, --help                      show this help message and exit
  -o OUT, --out OUT               path to images directory
  -k KEYWORD, --keyword KEYWORD   search query for API
  -p PER, --per PER               number of results per requests
  -m MAX, --max MAX               total results
```


## Step 2: Download images from URL file

-   Example: `python download_images.py -o 'images' -u 'cat.txt'`

```
usage: download_images.py [-h] -o OUT -u URLS [-s START]

optional arguments:
  -h, --help                show this help message and exit
  -o OUT, --out OUT         path to images directory
  -u URLS, --urls URLS      path to image urls file
  -s START, --start START   start number of image name
  -p' PAGE --page PAGE      page to crawl
```

## Acknowledgement
- The repo is based on https://github.com/18520339/image-search-downloader
- https://pyimagesearch.com/2018/04/09/how-to-quickly-build-a-deep-learning-image-dataset/
- https://pyimagesearch.com/2017/12/04/how-to-create-a-deep-learning-dataset-using-google-images/"# crawler-image-tools" 

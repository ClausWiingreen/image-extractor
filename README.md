# Image Extractor
A tool that extracts images from pdf files

## Dependencies
* poppler-utils
* imagemagick

## Installation
Copy the script where you want it. I would suggest a folder in your path such as /usr/local/bin. Make sure that the file is executable.

## Usage
```
image-extractor [OPTION]... FILE... 

Options:
  -h, --help            Display this help message
  -v, --version         Print the version info and exit
  -s, --min-imagesize   The process will remove all images smaller than this
                        value in pixels (defaults to 200)
      --no-pagenumbers  Add pagenumbers to the image files
      --no-merge        Do not automatically merge images with their mask
      --merge-type      Set the file extension for merged files (defaults to 
                        webp)
  -t, --target          Set the destination directory for all the images
                        (defaults to './images')
  -V, --verbose         Change the output to logs instead of progressbar
```

## Thanks to
* fearsize for his [ProgressBar](https://github.com/fearside/ProgressBar) which i based mine on.

## License

Copyright (C) 2020 Claus Wiingreen
This project is MIT licensed

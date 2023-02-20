# convert-images-into-WebP

## Introduction
Loading JPG files in web pages seems to be slow, so I try to use WebP.

WebP is a special file type developed by Google. It's designed to speed up the loading time of modern websites. More details: https://developers.google.com/speed/webp

Google provide various tools to convert images, and I choose to use `cwebp.exe`. It's downloaded from [here](https://storage.googleapis.com/downloads.webmproject.org/releases/webp/index.html).

## How to use it? (for Windows PowerShell)
Put your images in this folder and run:

`.\cwebp.exe -q 80 image-name.png -o image-name.webp`

For more options: https://developers.google.com/speed/webp/docs/cwebp
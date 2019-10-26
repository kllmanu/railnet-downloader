# railnet-downloader

Download newspaper & magazines from the OeBB railnet

## Usage

1. Connect to the `OEBB` passenger wifi of any Railjet/Cityjet
2. Accept the Terms of Use in your browser before
3. Run the script with the newspaper or magazine you're looking for

The script downloads all the pages (images) of the latest issue available and creates a PDF out of them.

## Dependencies

- [curl](https://curl.haxx.se/)
- [jq](https://stedolan.github.io/jq/)
- [img2pdf](https://gitlab.mister-muffin.de/josch/img2pdf)
- [xdg-user-dirs](https://freedesktop.org/wiki/Software/xdg-user-dirs/) (optional)

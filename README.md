# reformat-images
Simple tool for macOS (primarily designed for XCode projects) for converting all images with specified format to another format
## Dependencies:
For converting images imagemagick is used. You can install it using brew:
```console
brew install imagemagick
```
## Installation:
```console
git clone https://github.com/yasha424/reformat-images
cd reformat-images
mv reformat-images  /usr/local/bin/
chmod u+x /usr/local/bin/reformat-images
```
chmod u+x is used for making bash script executable.\
After intsallation open new terminal window and you are ready to go
## Usage:
### Enter project directory in terminal then write:
```console
reformat-images png heic
```
*AppIcon is untouched

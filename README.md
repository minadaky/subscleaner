# Subscleaner

## Dependencies

This script depends on [chardet](https://github.com/chardet/chardet) and [pysrt](https://github.com/byroot/pysrt).
Install them via pip3:
```
pip3 install --user pysrt chardet
```
or via virtual environment.

## Installation
Clone the repo and run
```
python3 setup.py install --user 
```
or `chmod +x` the script and copy it in a $PATH directory.

## Usage

Script will accept piped file names.  

```
find . -name '*.srt' | subscleaner
```

## Location of srt's
/Volumes/Emby/metadata/library


# Reddit WallLoad
[![Built with Python3](https://img.shields.io/badge/Built%20with-Python%203-red.svg)](https://www.python.org/)
[![GUI built with PyQt5](https://img.shields.io/badge/GUI%20built%20with-PyQt5-29B6F6.svg)](https://pypi.python.org/pypi/PyQt5)
[![License GPL-3.0+](https://img.shields.io/badge/License-GPL--3.0%2B-7E57C2.svg)](./LICENSE.md)


## Description
This is a simple tool I've created for day to day use to fetch wallpapers from https://www.reddit.com/r/wallpapers/.

- It fetches wallpapers from the hot section, attempts to download them and puts in a folder with a time stamp. 
e.g. A wallpaper from 19/03/2016 would be in /folder_where_RWD.py_is_located/data/wallpapers/19.03.2016/

- After downloading them, it displays the images for you to choose (Windows Only)

## Installation and Updating
With [Python 3](https://www.python.org/downloads/) installed, simply install PRAW (The reddit API) by typing the following on the console(CMD):

`pip install praw`

If the program states that the Reddit API is outdated, simply run:

`pip install --upgrade praw`

Also install PyQt 5 running the following on the console:

`pip install pyqt5`

Having done that, clone the repository into the desired folder, and it's ready for use!

## Usage
Simply run RWD.py to fetch and set new wallpapers. 

If you wish for the program to run without displaying the python console, simply rename RWD.py to RWD.pyw. (For windows only)

## Contributing
Contributions are greatly appreciated, feel free to make pull requests as to discuss and implement any changes/features you've developed.

## Planned Features
- [x] Convert imgur links to image links
- [x] Add subreddit chooser
- [x] Linux and OSX support
- [ ] Detect slashes and correct links using string manipulation
- [ ] Add upvote buttons for each wallpaper
- [ ] Add delete option for each wallpaper
- [ ] Add favorites section


## Authors
- TGLIDE

## License
This project is licensed under the [GNU GPL v3 License](./LICENSE.md)

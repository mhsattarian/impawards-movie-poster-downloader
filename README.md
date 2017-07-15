# PosterDownloader
Webscraper for downloading movie posters in the highest resolution available, using impawards.com as database


Keep in mind, I don't encourage downloading several times in a short time span, as impawards tend to get angry when you request them so many images at once. Try to space out your downloads

This program does the following:
* Asks you a movie
* Asks which of the found would you like
* Downloads every poster found in it's highest resolution available

Windows and Linux users:
* Download from 'releases' the latest one and extract everything
* After that, just start the PosterDownloader.exe (Windows) or write ./PosterDownloader in the terminal (Linux)

If you want to tweak and see the source code (written in Python 3.6):
* Just download from the repo page both "PosterDownloader.py" and "impawards.py" and start with 'python PosterDownloader.py'
* Keep in mind you need pip (default in Py3.4 onwards) and: requests, bs4 and lxml
# coursera-downloader

A command-line interactive coursera-downloader.

This project is based on 2 other projects:
  - [Coursera Downloader 1](https://github.com/coursera-dl/coursera-dl)
  - [Coursera Donwloader 2](https://github.com/jansenicus/www-coursera-downloader)

#### Before you run:
The script is tested with **Python3** and **Mac Sierra OS**.
No guarantee for the performance in other setting, but you can always try out first :)

#### To run:
1. download the repo zip or clone the repo: `git clone https://github.com/yingchi/coursera-downloader.git`
2. cd to the repo folder: `cd coursera-downloader`
3. open `coursera-downloader.py` with your favoriate editor, and change the 'path' value in 'default_args' to your favoriate path.
4. run the main script: `python coursera-downloader.py`

You will be prompted to provide your log in credentials. Your username and password will be saved to an encrypted files for next use.

You will then be prompted to input your other options. By default, a folder with the course name will be created under the
`coursera-downloader` folder to host all the files downloaded from `www.coursera.org`. If you do not ignore 'mp4' files, the downloading process may take a while.

#### Note: 
Materials that opens in a new tab, such as iPython notebooks can not be downloaded.
If you want to change the default settings, you can find it in the `coursera-downloader.py` file. 

欢迎feedback~ 都加油学习哟，笔芯~

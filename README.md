# Dictionary plugin for anki using jisho.org

# Description

   * Plugin for anki that implements a dictionary lookup that can import results as cards into anki.
   * Primarily made for my own needs, no intentions to actively distribute.
   * Use ctrl+character displayed left of the search result to add card to target deck.

## Status

   * Dosnt work with the new version of anki

## Resources

   * [Anki](http://ankisrs.net/)
   * [Jisho](http://classic.jisho.org/)

## Extra requirements

   * [bs4 (BeutifulSoup 4)](https://pypi.python.org/pypi/beautifulsoup4/)


## Install instructions

### Linux

#### Debian

    $ sudo apt-get install python-bs4
    $ git clone https://github.com/Magneli/Anki-japanese-dictionary-plugin---WIP.git ~/Documents/Anki/addons

#### Ubuntu

    $ sudo apt-get install python-bs4
    $ git clone https://github.com/Magneli/Anki-japanese-dictionary-plugin---WIP.git ~/Anki/addons

#### Fedora (22)

    $ sudo dnf install python-beautifulsoup4
    $ git clone https://github.com/Magneli/Anki-japanese-dictionary-plugin---WIP.git ~/Documents/Anki/addons

### Windows

    * Download zip file.
    * Unzip and put the contents of the unzippped folder inside the anki addon folder.
    * Download bs4 for python 2.7, unzip it and put the bs4 folder in the anki addon folder.

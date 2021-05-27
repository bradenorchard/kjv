# kjv

Read the Word of God from your terminal

Forked from [https://github.com/LukeSmithxyz/kjv.git](https://github.com/LukeSmithxyz/kjv.git) but with the Book of Mormon added.

I may add the rest of the standard works of The Church of Jesus Christ of Latter-day Saints eventually.

## Usage

    usage: ./kjv [flags] [reference...]

      -l      list books
      -W      no line wrap
      -h      show help

      Reference types:
          <Book>
              Individual book
          <Book>:<Chapter>
              Individual chapter of a book
          <Book>:<Chapter>:<Verse>[,<Verse>]...
              Individual verse(s) of a specific chapter of a book
          <Book>:<Chapter>-<Chapter>
              Range of chapters in a book
          <Book>:<Chapter>:<Verse>-<Verse>
              Range of verses in a book chapter
          <Book>:<Chapter>:<Verse>-<Chapter>:<Verse>
              Range of chapters and verses in a book

          /<Search>
              All verses that match a pattern
          <Book>/<Search>
              All verses in a book that match a pattern
          <Book>:<Chapter>/<Search>
              All verses in a chapter of a book that match a pattern

## Build

kjv can be built by cloning the repository and then running make:

    git clone https://github.com/bradenorchard/kjv.git
    cd kjv
    sudo make install

## License

Public domain

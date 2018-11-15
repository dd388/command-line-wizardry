# Warm-ups!

Here are some tasks to get you started.

## [Removing Spaces from Filenames](spaces "Removing Spaces from Filenames Warm-Up")

Your goal: Remove the spaces from the filenames and replace them with another delimiter. Depending on how you ambitious you feel, there are two ways you can do this.

* Starter: Rename JPGs to the following format:
    `Book_0123_001.jpg`

* Fancy: Rename JPGs to the following format:
    `Book0123_001.jpg`


## [Standard Refoldering](standard-refolder "Standard Refoldering Warm-Up")

Your goal: Group files together by a specific pattern.

Several books have been digitized and all of the pages from each book have been saved to a single directory, like so:

    Book123_page001.jpg
    Book123_page002.jpg
    ...
    Book128_page001.jpg
    Book128_page002.jpg
    ...

Your job is to create a folder for each book (represented by the first part of the filename) and place all of the corresponding files in these folders.

Your target organization is:

    Book123
    -Book123_page001.jpg
    -Book123_page002.jpg
    ...
    Book128
    -Book128_page001.jpg
    _Book128_page002.jpg

_Hint: You can't solve this with one command. In fact, you'll probably find yourself writing a few of them to make this happen._

## [Complex Refoldering](complex-refolder "Complex Refoldering Warm-Up")

Your target organization is the same as above, but some of the books have spaces between the book number and the page number and some have underscores between the book number and the page number.

## [Trickier Refoldering](trickier-refolder "Trickier Refoldering Warm-Up")

Your target organization is the same as above, but books have combinations of underscores and spaces separating the various components of the filename. _Hint: All files pertaining to a single book will have a consistent naming pattern._

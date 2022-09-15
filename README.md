# Word-HighLighter js
In this project we will be creating the same functionality as the find function (control + f in windows and command + f on mac)
of the browser.

The html markup has already been pre defined for you.

#paragraph-input div is a normal div, but it has contenteditable
property set to true which makes it possible to type inside it.
Here the user will enter the text they want to search from.

#word-input will take input for the word we want to highlight/find. We want to highlight each time a character is typed, just like browser find on page functions.


span#word-counterwill contain the number of words found


#ignore-case checkbox will decide whether we want to it to be case sensitive or not, be default it is. Upon changing it, the highlighted text also should change, as in the demo video

All the highlighted sections of the paragraph will have class="highlighted-text"(hint:- use span in order not to change text spacing )

class .highlighted-text is already defined for you

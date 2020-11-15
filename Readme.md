### WordCount.py
A common utility on Unix/Linux systems is a small program called "wc".  This program analyzes a file to determine the number of lines, words, and characters contained therein.

Write your own version of wc.  The program should accept a file name as input and then print three numbers showing the count of lines, words, and characters in the file.

SAMPLE OUTPUT
```
Enter a File Name: text.txt

Lines: 12
Words: 48
Characters:249
```
---
### WordIndex.py
We want to create a word index that keeps record of every word in a file, and what line numbers that word can be found on.
Using dictionaries in python, each word will have an associated list of line numbers.
```
words = {'hello': [2, 5] , 'world': [2, 4]}
```
This signifies that the word 'hello' is on lines 2 and 5; the word 'world' is on lines 2 and 4.

You should be able to print each word followed by the page line numbers of those words, like an index at the back of a textbook.

---

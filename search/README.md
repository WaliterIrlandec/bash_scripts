Search substring in files
=============

Simple Use: **search bob**
Try to find "bob" substring in all files in current directory with all subfolders
Displays information about the file name, line number and the line itself

+ Param (or usr keys):
  + $1: search string
  + $2: file name
  + $3: path

+ Default params:
  + $1: ''
  + $2: '*'
  + $3: './'

+ Keys:
  + -s: search string
  + -n: file name (use \\* for all)
  + -d: path
  + -l: list mode (only file names)
  + -a: additional strings


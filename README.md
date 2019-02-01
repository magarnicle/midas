# M*ult*ID*imension*A*l*S*preadsheet*
An N-dimensional spreadsheet with a Vim-inspired grammar.

## N-dimensional
Up to 9999 axes.

## Spreadsheet
View any two axes as a grid of cells.

## Vim-inspired grammar
Not just the token hjkl to move around, rather an actual *language*, with counts, motions, operators and objects.

### Counts
Many commands take a count to perform the command multiple times.

### Motions
Many commands operate in a direction. And, considering this is an *N-dimensional spreadsheet* there are up to 9999 axes that the motion can operate on (both 'forward' and 'back' along it).

### Operators
Actions to perform on objects include add, delete, edit, yank (copy) etc.

### Objects
Cells, rows, columns, axes, views (arbitrary pairings of axes displayed together).

## JSON
Midas files are just JSON files.

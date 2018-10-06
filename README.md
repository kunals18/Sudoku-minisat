# Sudoku-minisat
Quick install miniset
```
   make config prefix=$PREFIX
   sudo make install
```
Generate cnf file
```
   python sudoku.py dig.txt cnf
```
Generate miniset output file
```
   minisat cnf.txt out.txt
```
Parse the output file to get solution
```
   python sudoku.py out.txt parse
```

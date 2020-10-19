# LatinExplainer
##### Development of the this program is stopped.
##### Instead the code will be integrated into my own version of SukakuExplainer: https://github.com/1to9only/SukakuExplainer.

LatinExplainer is my modifications to SudokuExplainer to solve 9x9 latin squares.

LatinExplainer is SudokuExplainer without the 3x3 block constraint, the numbers 1-9 must appear exactly once in each row and column.

## Usage - GUI
```
java.exe -jar LatinExplainer.jar
```
![](/images/sample1.jpg)

## Usage - serate
```
java.exe -Xrs -Xmx500m -cp LatinExplainer.jar diuf.sudoku.test.serate --format="%g ED=%r/%p/%d" --input=puzzles.txt --output=output.txt
```

## Usage - manual
```
java.exe -cp LatinExplainer.jar diuf.sudoku.test.serate -m
```


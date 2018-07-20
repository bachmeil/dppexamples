Creating a mex file to be called from Octave

Example taken from [this page](https://octave.org/doc/interpreter/Working-with-Matrices-and-Arrays-in-Mex_002dFiles.html#Working-with-Matrices-and-Arrays-in-Mex_002dFiles)

This works with Octave 4.2.2. It doesn't work with 4.0.0, so you may need to upgrade your version of Octave.

To compile:

```
make example
```

The compilation steps in the Makefile were based on the output of mkoctfile for the C example using option `-v` for verbose output. Then open Octave and run the following:

```
b = randn (4,1);
mypow3(b)
```

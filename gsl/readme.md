The [GNU Scientific Library](https://www.gnu.org/software/gsl/)

Reproduces the documentation example on [this page](https://www.gnu.org/software/gsl/doc/html/poly.html)

You have to install all dependencies necessary to compile GSL programs with a C compiler. On Ubuntu, that should be

```
sudo apt-get install gsl-bin libgsl-dev
```

To make and run the C program:

```
make cprog
./poly
```

To make and run the D program:

```
make dprog
./dpoly
```

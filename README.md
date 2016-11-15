# To build
```
CC=pgcc mpicc -acc collective_acc.c -o acc.out
```

# To run
```
mpirun -gpu -n 2 ./acc.out
```

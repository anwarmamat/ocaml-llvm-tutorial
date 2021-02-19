# Example

```
make
```

```
clang -c -emit-llvm hello.c
```
```
./build/tutorial01/src/tutorial01.byte ./hello.bc
```
or redirect the output to a file
```
./build/tutorial01/src/tutorial01.byte ./hello.bc "$@"  2>>hello.ll
```
```
llc hello.ll
```
```
clang hell.s -o hello
```

now run 
```
./hello
```


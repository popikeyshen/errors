
## Errors


### Error 1
Popular darknet error
```
nvcc not found
```
```
export LD_LIBRARY_PATH=/usr/local/cuda/lib
export PATH=$PATH:/usr/local/cuda/bin
```

### Error 2
```
nvcc fatal   : Path to libdevice library not specified
Makefile:162: recipe for target 'obj/convolutional_kernels.o' failed
make: *** [obj/convolutional_kernels.o] Error 1
```

```
export PATH=/usr/local/cuda/bin:"$PATH"
```

silly_device_driver
====

Practice of making device driver

```
$ make
$ sudo insmod nyan.ko 
$ sudo mknod /dev/nyan c 333 1
```

```
$ make # After fixed your code
$ sudo rmmod nyan
$ sudo insmod nyan.ko 
```

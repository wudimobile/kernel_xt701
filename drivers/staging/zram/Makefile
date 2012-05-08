XVM = sub-projects/allocators/xvmalloc-kmod
EXTRA_CFLAGS	:=	-Wall

obj-y		+=	zram.o
zram-objs	:=	zram_drv.o zram_sysfs.o $(XVM)/xvmalloc.o
obj-y += lzo1x_compress.o lzo1x_decompress.o

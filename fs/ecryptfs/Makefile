#fix for -o2
EXTRA_CFLAGS += -Wno-maybe-uninitialized
#
# Makefile for the Linux 2.6 eCryptfs
#

obj-$(CONFIG_ECRYPT_FS) += ecryptfs.o

ecryptfs-objs := dentry.o file.o inode.o main.o super.o mmap.o read_write.o crypto.o keystore.o messaging.o miscdev.o kthread.o debug.o

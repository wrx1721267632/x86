# x86学习

nasm mbr.asm

qemu-img  create -f qcow disk.img 128M

dd if=mbr of=./disk.img bs=512 seek=扇区号

qemu disk.img


# Qemu-kvm
##Qemu介绍

qemu是什么，简单来说它是一个虚拟机的管理器，类似Virtualbox之类的。为了使虚机达到接近主机的性能，一般会结合kvm（或者Xen）对硬件虚拟化。kvm负责cpu+mem虚拟化，但kvm不能模拟其他设备；qemu负责模拟IO设备（网卡，usb等），两者结合能实现真正意义上的全系统仿真。kvm与qemu的结构如图所示：

具体可参考

```html

http://liushy.com/2017/04/29/libvirt-qemu/

```

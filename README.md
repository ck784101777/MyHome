# MyHome
提供两个文件一个是qcow2镜像文件，这是一个系统镜像文件用于快速装机，还有一个配置文件用于定义镜像

使用方式：
   1.将baseimg.qcow2移动到/var/lib/libvirt/images目录下
   2.将clone-vm7放到/usr/local/bin下，给执行权限 chmod +x /usr/local/bin/clone-vm7
   3.执行命令clone-vm7，输入整数创建虚拟机

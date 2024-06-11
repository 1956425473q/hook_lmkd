这是一个让lmkd不杀后台的程序

/data/local/tmp目录下或者其他拥有执行权限的目录下，cd到当前目录下并执行就可以了

可以用sudo /data/local/tmp/hook_lmkd {pid}命令执行，也可以进入程序后输入lmkd进程的pid执行

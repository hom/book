# `<sys/types.h>`定义基本系统数据类型

类型|说明
---|----
`clock_t`|时钟滴答计数器（进程时间）
`comp_t`|压缩的时钟滴答
`dev_t`|设备号（主和次）
`fd_set`|文件描述符集
`fpos_t`|文件位置
`gid_t`|数值组ID
`ino_t`|i节点编号
`mode_t`|文件类型，文件创建模式
`nlink_t`|目录项的链接计数
`off_t`|文件长度和偏移量（lseek）（带符号）
`pid_t`|进程ID和进程组ID（带符号）
`pthread_t`|线程ID
`ptrdiff_t`|两个指针相减的结果（带符号）
`rlim_t`|资源限制
`sig_atomic_t`|能原子性的访问的数据类型
`sigset_t`|信号集
`size_t`|对象长度
`ssize_t`|返回字节计数的函数（read/write）
`time_t`|日历时间的秒计数器
`uid_t`|数值用户ID
`wchar_t`|能表示所有不同的字符码

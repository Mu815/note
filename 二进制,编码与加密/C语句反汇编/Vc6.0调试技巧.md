查看汇编代码的方法

1.现下断点，然后F5
然后右键就出现了go to desassembly

<img src="../../img/image-20210205044854448.png" alt="image-20210205044854448" style="zoom:50%;" />

2.或则直接按下F10进入调试模式



如果没有跑完代码直接重构代码会出现以下境况


![image-20210205045228126](../../img/image-20210205045228126.png)

不能再写入

再次尝试选择否就会执行之前的代码

![image-20210205045553516](../../img/image-20210205045553516.png)

所以再调试最好看完汇编跳出主函数结束进程

在调试模式下



点两下这个run tu cursor可以帮助跳出这个循环



![image-20210205050110842](../../img/image-20210205050110842.png)
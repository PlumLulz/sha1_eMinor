# sha1_eMinor
sha1(eMinor--$salt.sha1(eMinor--$pass--})--}) Pure Hashcat Kernel

Install:  
Add the module_92000.c file into the ./src/modules directory.  
Add the m92000_a0-pure.cl, m92000_a1-pure.cl, and m92000_a3-pure.cl files into the ./OpenCL/ directory.  
Run make in the root hashcat directory  
Run rm -rf ./kernels in the root hashcat directory  

![image](https://i.imgur.com/rLWIvjz.png)

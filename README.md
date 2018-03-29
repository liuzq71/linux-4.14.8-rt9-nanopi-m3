# building
1. `make ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- nanopim3_defconfig`
2. `make ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- menuconfig`
     
   ```
   Kernel Features --->
     Preemption Model (Fully Preemptible Kernel (RT))  --->
        (X) Fully Preemptible Kernel (RT) 
   ```
  
3. `make ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- Image -j4`

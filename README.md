# OpenWCH-SDK
Open WCH RISC-V Chip SDK



## Install Toolchain

http://www.mounriver.com/download

Download Toolchain for Linux: MRS_Toolchain_Linux_x64_V1.80.tar.xz

```shell
wget http://file.mounriver.com/tools/MRS_Toolchain_Linux_x64_V1.80.tar.xz
```

Extract Toolchain && Add to PATH

```shell
sudo tar -xvf MRS_Toolchain_Linux_x64_V1.80.tar.xz -C /opt
export PATH=/opt/MRS_Toolchain_Linux_x64_V1.70/RISC-V\ Embedded\ GCC/bin:$PATH
```


## Build

```shell
cd examples/driver/gpio
mkdir build && cd build
cmake ..
make
```


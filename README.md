# RISC-V-SOC-TAPEOUT-PROGRAM-VSD
week0
## YOSYS
```bash
$ sudo apt update
$ sudo apt install -y \
    build-essential clang bison flex libreadline-dev \
    gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 \
    libboost-system-dev libboost-python-dev \
    libboost-filesystem-dev zlib1g-dev
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ make -j$(nproc)
$ sudo make install
![Daigram](https://github.com/chaitubellana-droid/RISC-V-SOC-TAPEOUT-PROGRAM-VSD/blob/main/Screenshot%20from%202025-09-20%2013-00-01.png?raw=true)




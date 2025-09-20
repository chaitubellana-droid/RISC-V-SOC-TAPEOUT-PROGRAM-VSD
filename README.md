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


<img  src="https://github.com/user-attachments/assets/5743fb92-412f-45e0-af9e-2e2a2d776726" width="786" height="470" alt="image">





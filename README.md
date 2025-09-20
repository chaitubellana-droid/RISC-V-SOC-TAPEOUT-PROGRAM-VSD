# RISC-V-SOC-TAPEOUT-PROGRAM-VSD
# # week0
# Yosys

```bash
$ sudo apt update
$ sudo apt install -y build-essential clang bison flex \
  libreadline-dev gawk tcl-dev libffi-dev git \
  graphviz xdot pkg-config python3
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ make -j$(nproc)
$ sudo make install




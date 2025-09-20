swaminath-vsd<details><summary>Day 0 - Tools Installation </summary>Day 0 - Tools InstallationYosys$git clone [https://github.com/YosysHQ/yosys.git$](https://github.com/YosysHQ/yosys.git$) cd yosys 
$ sudo apt install make
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make 
$ sudo make install
<img width="575" alt="Yosys output" src="yosys version and installation.png">Icarus Verilog$ sudo apt-get install iverilog
<img width="702" alt="Icarus Verilog installation command line output" src="iverilog installation.png">GTKWave$ sudo apt update
$ sudo apt install gtkwave
<img width="604" alt="GTKWave installation command line output" src="gtkwaveformsinstallation.png"></details>

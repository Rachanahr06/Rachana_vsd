**To install yosys**

$ sudo apt-get update 

$ git clone https://github.com/YosysHQ/yosys.git 

(If make is not installed.
$ Sudo apt update)

$ cd yosys $ sudo apt install make (If make is not installed please install it)

$ sudo apt-get install build-essential clang bison flex \ libreadline-dev gawk tcl-dev libffi-dev git \ graphviz xdot pkg-config python3 libboost-system-dev \ libboost-python-dev libboost-filesystem-dev zlib1g-dev

•	Yosys depends on git submodule which Initialize the submodule, which means registering it in your local Git configuration.

$ git submodule update --init --recursive

$ make config-gcc 

$ make 

$ sudo make install
<img width="1251" height="341" alt="yosys" src="https://github.com/user-attachments/assets/ea88f486-657c-4834-b4e1-b55ce54bc998" />


**To install iverilog**

$ sudo apt-get update

$ sudo apt-get install iverilog
<img width="1007" height="338" alt="iverilog" src="https://github.com/user-attachments/assets/1eb6dcfd-11cb-42bd-944c-a6c69d916ed8" />


**To install gtkwave**

$ sudo apt-get update

$ sudo apt install gtkwave

<img width="1247" height="572" alt="gtkwave" src="https://github.com/user-attachments/assets/14aca286-4830-4b9e-94bf-4defc7f779fb" />


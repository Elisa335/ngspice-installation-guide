# ngspice-installation-guide

**install the ngspice-[version].tar.gz**

**extract the tar file**
`tar -zxvf [file]`

**install the dependencies**
`sudo apt install bison flex libx11-dev libxaw7-dev libxmu-dev libxext-dev libxrender-dev libfreetype-dev libfontconfig-dev libreadline8 libreadline-dev`

**compile and install ngspice**
`./configure`
`make clean`
`make`
`sudo make install`

**use ngspice**
`ngspice [file]`

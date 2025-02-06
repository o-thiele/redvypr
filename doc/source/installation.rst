Installation
============

Systems
-------

Raspberry Pi4
^^^^^^^^^^^^^
Installed on a Raspberry Pi4

sudo apt-get install python3-pyqt5 python3-pyqtgraph python3-netcdf4 python3-yaml python3-setuptools python3-serial python3-xlsxwriter

Debian 11 (Bookworm)
^^^^^^^^^^^^^^^^^^^^
Installed on a debian bookworm AMD64 laptop

sudo apt-get install python3-pyqt5 python3-pyqtgraph python3-netcdf4 python3-yaml python3-setuptools python3-serial python3-xlsxwriter 

Windows 10 with Anaconda
^^^^^^^^^^^^^^^^^^^^^^^^

Conda packages to install

Conda 2.1.0
conda install pyaml pyserial pyqtgraph netcdf4 xlsxwriter

Command line interface
----------------------
redvypr can be configured by command line arguments
For example::
  
  redvypr -p . -hn hf -a csvlogger,s,name:csv_raw,a:1,pi=3.1415,filepostfix:HF_raw,datastreams:"'['§.*§/§DHF_raw.*§','§.*§']'"

# Summary

Process-Monitor is an application for Linux distros which displays the real time information of all the running processos on the Linux system sych as CPU usage, RAM usage and much more related informations. It is a console application built using ncurses library.

## To setup and compile on your linux system

1. Clone repository onto your local machine
```
cd /home/workspace/ (for example)
git clone https://github.com/anikket786/system_monitor_for_linux
```
2. Install `ncurses` package if not installed on your system
```
sudo apt-get install libncurses5-dev libncursesw5-dev
```
4. Compile and run
```
g++ -std="c++17" main.cpp -lncurses
./a.out
```
5. In case of error that looks like the following: 
```
root@77e30fca8a01:/home/workspace/CppND-Object-Oriented# ./a.out
*** %n in writable segment detected ***
                                      Aborted (core dumped)
```
just keep trying `./a.out` and it should work eventually!

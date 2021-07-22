# CMake.sh
Bash script for setting up CMake on Ubuntu Linux versions: `16.04, 18.04 and 20.04`

## Usage
1. `git clone https://github.com/naftalimurgor/CMake.sh.git`
2.  `cd CMake.sh`
3. `sudo chmod +x install-cmake.sh`
4. Then excute script to setup cmake like:  
```bash
$ ./install-cmake.sh
```

## verify installation
To check installation, run:
```bash
$ cmake --version
```
If the installation completed successfully, you'll see output like below:
```bash
cmake version 3.5.1

CMake suite maintained and supported by Kitware (kitware.com/cmake).

```
# LICENSE
Installation script is provided as is from [Kitware APT Repository](https://apt.kitware.com/)

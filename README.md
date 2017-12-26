# nuclide-cpp-example
Barebone setup files needed for nuclide integration with C++

## Reqirements
* Nuclide
* CMake (>= 3.0); 2.8 and above should also work; just update config.
* Make

## Usage
```sh
cd nuclide-cpp-example
cmake .
make
```

This will generate a binary which you can execute using: `./myout`. But more importantly, now in Atom, with nuclide,
you'll see auto complete, jump to defintion and other C++ integration. 

## Nuclide C++ documentation
For more details, see: https://nuclide.io/docs/languages/cpp/

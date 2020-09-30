# robotology-vcpkg-binary-ports
Collection of vcpkg ports available on limited platform just in binary form. 

## Usage

To use this repo, you will need to specify to `vcpkg` to use the ports contained in this repo using
the [`--overlay-ports` option](https://github.com/microsoft/vcpkg/blob/master/docs/specifications/ports-overlay.md). 

For example, you can first clone this repo:
~~~
git clone https://github.com/robotology/robotology-vcpkg-binary-ports
~~~

Then, to install the `ipopt-binary` port, run `vcpkg` with the following options: 
~~~
./vcpkg.exe --overlay-ports=<repo_parent_directory>/robotology-vcpkg-binary-ports install ipopt-binary:x64-windows
~~~

## Available ports 

| Port name | Official vcpkg triplet for which it is available | 
|:---------:|:------------------------------------------------:|
| [`ensenso-binary`](ensenso-binary)| `x64-windows`                | 
| [`esdcan-binary`](esdcan-binary)| `x64-windows`                | 
| [`ipopt-binary`](ipopt-binary)| `x64-windows`                | 
| [`casadi`](casadi)| `x64-windows`                | 

# Software-Installation-Commands

## Installing Julia, Python, Gurobi on a Linux server using Putty

0. General platform specific instructions to be found here: https://julialang.org/downloads/platform.html

1. Download latest versions of julia, gurobi, and python for Linux. They will likely be tar files of type .gz extension. Extract the files:   https://www.interserver.net/tips/kb/extract-tar-gz-files-using-linux-command-line/

2. Editing .bashrc file to include path to Julia, python and Gurobi executables in PATH EV. 
https://askubuntu.com/questions/953093/installing-julia-v0-6-on-linux-ubuntu-16-04

3. Add relevant packages: Pkg.add("ABC")

4. Run the .jl file using "include("/A/B/C/abc.jl")

# Software-Installation-Commands

## Installing Julia, Python, Gurobi on a Linux server using Putty

0. General platform specific instructions to be found here: https://julialang.org/downloads/platform.html

1. Download latest versions of julia, gurobi, and python for Linux. They will likely be tar files of type .gz extension. Extract the files:   https://www.interserver.net/tips/kb/extract-tar-gz-files-using-linux-command-line/

2. Editing .bashrc file to include path to Julia, python and Gurobi executables in PATH EV. 
https://askubuntu.com/questions/953093/installing-julia-v0-6-on-linux-ubuntu-16-04

	The file will look something like this:  # .bashrc

	[insert hash here] Source global definitions
	if [ -f /etc/bashrc ]; then
	. /etc/bashrc
	fi

	[insert hash here] User specific aliases and functions
	export GUROBI_HOME="/home/z/zulqarnain/gurobi/gurobi752/linux64"
	export PATH="${PATH}:${GUROBI_HOME}/bin"
	export LD_LIBRARY_PATH="${LD_LIBRARY_PATH}:${GUROBI_HOME}/lib"
	export GRB_LICENSE_FILE="$HOME/gurobi.lic"
	export PATH=$HOME/bin:$PATH
	export PATH="${PATH}:/home/z/zulqarnain/Julia/julia-0d7248e2ff/bin"
	export LD_LIBRARY_PATH="${LD_LIBRARY_PATH}:/home/z/zulqarnain/Julia/julia-0d7248e2ff/lib"
	export LD_LIBRARY_PATH="${LD_LIBRARY_PATH}:/home/z/zulqarnain/Julia/julia-0d7248e2ff/lib/julia"

3. Add relevant packages: Pkg.add("ABC")

4. Install Gurobi License: https://user.gurobi.com/download/licenses/academic/64c37766-e4fe-11e7-ac4a-0a4522cc772c , https://user.gurobi.com/download/licenses/free-academic

5. Run the .jl file using "include("/A/B/C/abc.jl")

# Modeling

http://www.laurentlessard.com/teaching/cs524/slides/19%20-%20logic%20constraints%20and%20integer%20variables.pdf





# Job Hunt

## OR Analyst:  
1. APML, SQL, relational databases, object oriented programming, Simul8, network modeling, Perl, Ruby, R, SAS, SQL, Python
2. Experience prototyping and developing software in traditional programming languages (C++/ Java/ Python/Perl.), Data Mining, 
3. Familiarity with enterprise-wide application development life-cycle

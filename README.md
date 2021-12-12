# Sequential and Parallel Dijkstra Shortest Path Algorithm (Using OpenMP)

## Installation

Windows

• Download TDM-GCC : https://www.csc.tntech.edu/pdcincs/resources/modules/tools/updated/TDM-GCC-64.zip and unzip it <br>
• Open a command prompt and run mingwvars.bat from the folder

Mac OS

• Install homebrew using /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"<br>
• Install gcc using /usr/local/bin/brew install gcc <br>
• Use g++-11 as the compile command <br>

## Commands

<code>g++-11 -o Sequential_Dijkstra Sequential_Dijkstra.cpp -fopenmp</code><br>
<code>g++-11 -o Parallel_Dijkstra Parallel_Dijkstra.cpp -fopenmp</code>


## References

Introduction to Parallel Computing, 2nd ed. by A. Grama, G. Karypis, V. Kumar, and A. Gupta, Pearson, 2003

An Introduction to Parallel Algorithms, 1st ed. by J. JáJá, Addison-Wesley, 1992

Programming Massively Parallel Processors: A Hands-on Approach, 3rd ed. by D. B. Kirk and W. W. Hwu, Morgan Kaufmann, 2016

Introduction to Algorithms, 3rd ed. by T.Cormen, C. Leiserson, R.Rivest and C.Stein, MIT Press, 2009

# Alpha Centauri
Alpha Centauri is the closest star system to the Sun, located at a distance of just 4.37 light years or 1.34 parsecs from Earth. The system consists of Alpha Centauri A and Alpha Centauri B. It is sometimes known as Alpha Centauri AB (α Cen AB).

# Alpha Centauri Orbit Simulation
We aim to compare the runtime for Alpha Centauri binary star system orbit simulation using the N-body model previously performed in Python(Interpreted) now implemented in C (Compiled).

### N-body benchmarks by time
| x |  code source |  secs |   mem |   gz |  cpu |   cpu load   | 
|---|--------------|:-----:|:-----:|:----:|:----:|:------------:|
|1.1| __C__ gcc #4 |  9.12 | 1,176 | 1490 | 9.12 | 1% 100% 2% 2%|
|102| __Python__ 3 | 13 min| 10,324| 1196 |13 min| 95% 1% 5% 0% |

souce: http://benchmarksgame.wildervanck.eu/nbody.html

## Interpreted vs Compiled Programming Languages
In a compiled language, the target machine directly translates the program. In an interpreted language, the source code is not directly translated by the target machine. Instead, a different program, also know as the interpreter, reads and executes the code.

### Compiled languages
Compiled languages are converted directly into machine code that the processor can execute. As a result, they tend to be faster and more efficient to execute than interpreted languages. They also give the developer more control over hardware aspects, like memory management and CPU usage.
Examples of pure compiled languages are C, C++, Erlang, Haskell, Rust, and Go.

### Interpreted Languages
Interpreters run through a program line by line and execute each command.
Examples of common interpreted languages are PHP, Ruby, Python, and JavaScript.

# Prerequisites
Code written in C 
Please see the file [requirements.txt](requirements.txt) for more details.

# Comparing times
| x |  code source |  mins |   
|---|--------------|:-----:|
|1| __Python__ 3 | 8.28 min|
|2| __C__ gcc #4 |  20.50 min | 

# Comparing results
## Python
<img src="alpha_centauri.png" width:100px />

## C
![](AlphaCenteuri2.gif)


# License
This project is licensed under the GNU General Public License - see the [LICENSE](LICENSE) file for details


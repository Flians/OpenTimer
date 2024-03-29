# Monthly Technical Reports

This page summarizes the change logs of OpenTimer on a monthly basis.

## 11/2018

### News

+ OpenTimer won the best tool award in the 1st Workshop of Open-source EDA Technology (WOSET)

### Improvements

+ rename action API, report_at, report_rat, report_slack, etc. to be consistent with shell commands


---

## 10/2018

### News

+ Finished the first quarterly meeting with DARPA

### Improvements

+ fixed several bugs in path report
+ integrated with the newest cpp-taskflow module
+ rename builder API, read_celllib, read_verilog, create_clock, etc. to be consistent with shell commands

---

## 09/2018

### News

+ OpenTimer is selected as the golden timer of [TAU19 Contest][TAU19]
+ OpenTimer wiki is online

### Improvements

+ added dynamic programming algorithms to speed up shortest path finding
+ added strongly connected component (SCC) analysis to break loops
+ added command to report the aggregated cell areas in the design
+ added command to report the static leakage power of all cells in the design
+ added several examples to demonstrate the usage of OpenTimer
+ added support for asynchronous timing contraints (removal and recovery)
+ added clang++ compiler support
+ added support for explicit redirection of stdin to a file
+ improved the path report formats

---

## 08/2018

### Improvements

+ various runtime and memory performance improvements
+ forked the [Parser-SPEF][Parser-SPEF] project under MIT license to isolate the module of SPEF parsing
+ added travis continuous integration
+ added regression benchmarks from TAU contests (generated by IBM Einstimer)
+ added several examples for the usage of OpenTimer
+ added path-based analysis module to report top-K critical paths
+ added unit support for power, resistance, time, voltage, and current

## Fixes

+ Fixed the path generation bug
+ Fixed the suffix tree bug

---

## 07/2018

### News

+ OpenTimer v2.0 (alpha) released
+ DARPA IDEA invested in OpenTimer - thanks the program manager [Andreas Olofsson][Andreas Olofsson]

### Improvements

+ rewrote OpenTimer in C++17
+ created OpenTimer organization and repository on GitHub
+ changed the build system to CMake
+ adopted [Cpp-Taskflow][Cpp-Taskflow] to implement parallel incremental timing
+ integrated Synopsys Tap-in Synopsys Design Constraints Parser
+ added JSON module to convert SDC parser data to OpenTimer internal data structure

* * *

[Andreas Olofsson]:      https://github.com/aolofsson
[Cpp-Taskflow]:          https://github.com/cpp-taskflow/cpp-taskflow
[Parser-SPEF]:           https://github.com/OpenTimer/Parser-SPEF         
[TAU19]:                 https://sites.google.com/view/tau-contest-2019/home

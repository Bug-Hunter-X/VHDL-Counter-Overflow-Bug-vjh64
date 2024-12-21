# VHDL Counter Overflow Bug
This repository contains a VHDL code example demonstrating a potential overflow bug in a simple counter. The counter is intended to count from 0 to 15, but there's a subtle issue that could cause unexpected behavior.  The bug is explained in the `bug.vhdl` file and a corrected version is provided in `bugSolution.vhdl`.

The bug highlights a common mistake when working with integer ranges in VHDL: not explicitly handling the case where the counter reaches its upper limit and then wraps around.
# Deustch Oracle Algorithm
Quil implementation of the famous deutsch oracle quantum algorithm (just the 2 bit version).

This is the first algorithm with a super-polynomial speedup over classical computing!

Microsoft made a [great video](https://www.youtube.com/watch?v=F_Riqjdh2oM) about it.

To run it make sure you have riggeti's [quantum computing sdk](https://qcs.rigetti.com/sdk-downloads)
and run 
```bash
cat deustch.quil | qvm
```
If the black box contained a constant, then `|11>` will be the output.
If it instead contained the variable function, then `|10>` would be the output.

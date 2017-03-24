We provide a dataset derived from snap assembly experiments of a male and female plastic camera mold parts. The male part consists of 4-cantilever snap assemblies. The assembly strategy and experimental details are presented in detail here and here.

The snap assembly has performed with a HIRO robot using the 6 DoF right arm and we have gathered success and failure data. We have also conducted the experiment with one and two arms for success and failure data.

Each experiment yields: cartesian, wrench, and joint angle data as well as a state vector of transition times between 4 sub-tasks in the snap assembly (guarded approach, alignment, insertion, and mating).

Data Format

For each of the three robot quantities is:
time_step indep_var1 indep_var2 … indep_var n. 

For the state vector of transition times, there are 4 entries:
start_approach
start_alignment
start_insertion
start_mating

All data is covered by the Open Data Commons Open Database License (ODbL). See inside each folder.

This program executes the Bidirectional Pulse algorithm for the Least Expected Travel-Time Path Problem, 
as reported in https://doi.org/10.1016/j.cor.2021.105671.

The program must be in the same path as a "data" file folder. This folder must contain the STD networks' files 
and the origin-destination pairs on which the algorithm will be tested in the file "instances-LET.txt."

To run the algorithm, access the command prompt and run the following command: LET-Pulse.exe X, 
where X is the instance number you want to execute (it will execute the instance in line X-1 of the "instances-LET.txt" file). 
You can also run batches of experiments using a ".bat" file. 
See the examples (SiouxFallsSTD and BarcelonaSTD) to understand format requirements. 

The results are reported in the file "results-LET.txt", including the optimal solution and the running time (in milliseconds). 
This program has a running time limit of 600 seconds. 

If you have any questions, feel free to contact me at d.yamin@uniandes.edu.co.   
 
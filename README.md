# HetDMI
This is the implementation of HetDMI algorithm using Java programming language. the algorithm gets some genes as input seeds and generates disease modules using those seeds. 
The seeds can be pass through the algorithm using "~/data/seeds.conf" file. each line of this file represents the input seed of one of the diseases studied in the study. please take care of white spaces or any other special characters at the beginning or at the end of the seed lists. if you choose a gene as a seed and this gene is not in the network, an exception will be throw in the program.  
The default meta-path set to GPG because most the results presented in the paper are based on this meta-path. This default meta-path can be easily changed via modifying the source and recompile it again. 
All the data to generate the Heterogeneous biological network also located in the data directory.
if you have any questions, feel free to contact "mahdieh.ghasemi@ut.ac.ir."

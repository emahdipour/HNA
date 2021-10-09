# HNA
Hybrid SFLA-CSO Network Aligner

Author: Elham Mahdipour

This is HNA (Hybrid SFLA-CSO Network Aligner) program, and implemented by Elham Mahdipour that is assistant professor, department of Computer Engineering, Khavarn Institute of Higher Education, Mashhad, Iran. 

You can run the program from first to end and see all the results, but since the population generation process can take a time depended on the node numbers of networks, you can use the populations stored in each program. We saved the populations as the pair of related species that you can see in the input folder and load them on program, such as "mm-ce-pop.pickle". Also you need another file such as "mm-ce-base_permute.pickle". Please upload data files on root of jupyter notebook or subfolder.

Therefore, you must run follow steps:
1) Run all cells in "Load Graphs", "Swap Graphs", "Define Target Graph",and "Compute Score for create similarity matrix" sections.
2) If you will use saved population, please upload related pickle on root of jupyter notebook, then go "load population" cell and run them; else, please run "multi tasking for initial population", "multi processing for speed up", and "Initialization such as MeAlign" cells. 
3) Run all remains cells to create results. 

The requirement data is available in Biogrid dataset. You can download data from https://downloads.thebiogrid.org/BioGRID/Release-Archive/BIOGRID-3.5.170/ and prepare them such as files in input folder. 

Please feel free and contact to me (elham.mahdipour@gmail.com) if there are any problem.

All copyright reserved by the authors.

Best Regards,
Elham Mahdipour
Assistant Professor, Department of Computer Engineering, Khavarn Institute of Higher Education, Mashhad, Iran. 




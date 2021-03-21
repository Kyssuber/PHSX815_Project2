# PHSX815_Project1

This repository contains two principal programs: DieRollFaceThree.py and DiceAnalysis.py. Random.py contains the random class used to create
categorical distributions given the probabilities of each die face.

Use:
DieRollFaceThree.py --> in a command line, input "python DieRollFaceThree.py -seed number -p1a_3 number -p1b_3 number -Nroll number -Nexp number -outputH0 filename -outputH1 filename
Default Nexp = Nroll = 1; default output files False.
Note: p1a_3 and p1b_3 represent the probabilities for rolling face 3 for die type a and die type b, respectively. The default, as well as that used for the report's data analysis, assumes type a to be fair.
Output, if desired, gives textfile(s) containing sample data given H0 and/or H1.

DiceAnalysis.py --> in a command line, input "python DiceAnalysisCat.py -input0 filename_H0_data -input1 filename_H1_data -prob0 list
Each probability list should contain fraction elements, with each probability representing the chance of rolling any one face. E.g., for a fair die, [1/6, 1/6, 1/6, 1/6, 1/6, 1/6]. p0 is optional input parameter if assuming fair die (default is fair).
Output will be critical_lambda, beta, incidence of 3 distribution plot for both hypotheses, and LLR distribution plot for both hypotheses.


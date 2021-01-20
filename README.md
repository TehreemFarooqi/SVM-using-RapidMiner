# Implementation of SVM on RapidMiner using UCI heart dataset
The file implements SVM algorithm that is then tested on UCI heart dataset (attached) and divides the data into train-test sets with 80-20 percentage. The algorithm gives 81.97% accuracy without any feature selection or synthetic features. 

### Update:
I edited the data to add synthetic, random and derived features to check if I can improve accuracy. I also used the optimization module in RapidMiner to apply four different types of optimization algorithms namely:
- Forward Selection
- Backward Elimination
- Minimum Redundancy Maximum Relevance (MRMR)
- Genetic Algorithms

The results after applying all these techniques separately are given in the attached PDF. Summarizing these results, we see that SVM gives the best results on original features i.e. 81.97% and its accuracy decreases if we add any other features to 80.33%. With optimization module, we can see that use of genetic algorithms for optimization improves the accuracy of SVM to 90.16%.

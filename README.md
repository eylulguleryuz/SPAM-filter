# SPAM Filter
A SPAM classifier using Bayes theorem. 
It also investigates a dependency between classifier parameters and efficiency of the classifier output, in other words, dependency of number false positive and true negative number on 
```
1.	number N of analyzed lexemes, 
2.	spamicity value of unseen lexeme.
```

## The steps
In the Jupyter Notebook file, investigation of the performance by changing the spamicity value, the number of analyzed lexemes, 
and the threshold of the spamicity value can be found.

According to the tests, the best-performing parameters are:
```
64 for the number N of analyzed lexemes, 
0.4 for the spamicity value of unseen lexeme, 
0.01 for the threshold value
```

With these parameters, a model is created:
```
Best performance:
Number of SPAM files classified as HAM (false positive): 10
Number of HAM files classified as SPAM (false negative): 1
Ratio of correctly classified files (%): 94.5
```
The results are quite promising and can be further improved by testing on more precise values.

# VedantsharmaDevngiriscript
Classify Character from Images in Devanagari script

A sample of the dataset is analyzed using various algorithms, and their scores and computational costs are compared.

Algorithm 	       Accuracy (in percent) 	Total Time (in seconds)
RidgeClassifier         	42.3384 	         00.712410
BernoulliNB 	            51.2742 	         00.168973
GaussianNB 	              39.6972 	         01.411730
ExtraTreeClassifier 	    31.1093 	         00.109071
DecisionTreeClassifier   	36.5119 	         04.080331
NearestCentroid 	        53.0247 	         00.127525
KNeighborsClassifier 	    72.1442 	         36.413726
ExtraTreesClassifier 	    57.4804 	         00.563712
RandomForestClassifier 	  54.3047 	         00.932044

The final result, using Extremely Randomized Decision Forest Classification Algorithm with 256 trees gives an accuracy score of 92%.

# GLFR benchmark

GLFR benchmark is a program to generate synthetic networks with community structure for testing community detection algorithms. GLFR benhcmark is a generalization of the LFR benchmark that accounts for the heterogeneity in community mixing fractions and outliers. 
 
Network parameters of the GLFR benchmark:

-N: number of nodes

-k: average degree of nodes

-kmax: maximum degree of nodes

-smin: minimum size of communities

-smax: maximum size of communities

-gamma: exponent for degree sequence

-beta: exponent for communiy size sequence

-mu: average of the fractions of external links of communities

-delta: maximum distance from the fractions of external links of communities to mu

-ns: number of outliers

The original implemenation of the LFR benchmark (with the homogeneity of community mixing fractions and without outliers) created by Lancichinetti can be download at https://sites.google.com/site/santofortunato/inthepress2		

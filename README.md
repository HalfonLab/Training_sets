**SCRMshaw** requires “training data” in the form of known CRMs with common function. The “common function” of a set of CRMs can be defined in various ways, and broadly or narrowly. Ideal characteristics are an ongoing area of investigation. As a general rule, the most successful training datasets consist of CRMs with similar (although not necessarily identical) patterns based on well-defined anatomical classifications such as “midline,” “wing disc,” and “ventral nerve cord.” We expect that the more broadly defined the class, the wider the functional range of the resulting CRM predictions will be. This allows the user to search for a more-or-less specific set of results. We have found that even very broadly constituted datasets give a higher percentage of true-positive results than training data composed of randomly selected noncoding sequences, suggesting that as a whole CRMs are enriched for informative subsequences.

All of these training sets here include, for each constituent CRM from *D. melanogaster*, orthologous sequences from 10 related *Drosophila* species; inclusion of these sequences improves SCRMshaw’s predictive power. Custom training sets can be developed by downloading selected sets of CRMs from the REDfly database (http://redfly.ccr.buffalo.edu) and following the steps in the protocol section 3.2 (Kazemian & Halfon 2019)).

Following is the detail of directories

|-------CRM.train

|

|-------final_combined_48Tsets

|

|------new74Tsets_Feb2020



**Data description**
1) **CRM.train**:
This is the first/oldest directory of our training data. Most of the sets in this directory were originally defined in Ivan et. al., 2008 and it also includes few of the customized training set.

2) **final_combined_48Tsets (Recommended)**:
This is our current preferred collection of training data, composed of a mix of older and newer training sets. All of these training set have passed a cutoff in which the training set sensitivity better than or equal to a randomly-composited set’s sensitivity. Ranking of each set is also given in the file 202007OldMix48_codeRanking.txt, which includes 3 broad categories, good ,intermediate and poor. Details of this ranking can be found in the subsequent directory.

3) **new74Tsets_Feb2020**:
This directory, compiled on Feb of 2020, has 74 training sets that are derived from the *Drosophila* Gross Anatomy Ontology (DAGO).


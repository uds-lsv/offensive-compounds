# offensive-compounds
This repository contains all new resources we created for our NAACL 2019 paper "Detecting Derogatory Compounds – An Unsupervised Approach" by Michael Wiegand, Maximilian Wolf, Josef Ruppenhofer. It also includes further details regarding our experimental set-up for which no space was available in the actual paper.

# *supplementaryNotes.pdf*
The file *supplementaryNotes.pdf* describes various details regarding our experiments, e.g. creation of the gold standards, hyperparameter tuning, pseudocode, notes on replicating the "unigram approach" from Wiegand et al. (2018) on German data etc.


# subdirectory *Gold Standards*
The subdirectory *Gold Standards* comprises the two gold standards used in this work:
1) *goldstandard.compounds.txt*

This is the gold standard of German noun-noun compounds which was manually annotated.
Each compound is labeled as either DEROGATORY or OTHER.
The format of each line is
<compound>	<modifier>	<head>	<LABEL>


2) *goldstandard.unigrams.txt*

This is the gold standard from Wiegand et al. (2018) translated to German.
It comprises exclusively unigrams representing negative polar expressions. They are either labeled as DEROGATORY or OTHER.
The format of each line is
<EnglishExpression>	<GermanTranslation>	<LABEL>
Note that due to cultural differences, some of the original English expressions could not be translated. These cases are indicated by "?" in the column for the German translation.

# attribution
This data set is published under [Creative Commons Attribution 4.0](https://github.com/uds-lsv/offensive-compounds/blob/master/LICENSE).

# acknowledgments
The work was partially supported by the German Research Foundation (DFG) under grants RU 1873/2-1 and WI 4204/2-1,
the Leibniz Science Campus “Empirical Linguistics and
Computational Modeling”, funded by the Leibniz Association under grant no. SAS-2015-IDS-LWC and
by the Ministry of Science, Research, and Art (MWK) of the state of Baden-Württemberg.



# contact information 
Please direct any questions that you have about this software to Michael Wiegand at Leipniz ScienceCampus (Mannheim/Heidelberg).

Michael Wiegand	      email: wiegand@cl.uni-heidelberg.de


# references

Michael Wiegand, Josef Ruppenhofer, Anna Schmidt and Clayton Greenberg: "Inducing a Lexicon of Abusive Words -- A Feature-Based Approach", in NAACL/HLT, 2018.


Michael Wiegand, Maximilian Wolf, Josef Ruppenhofer: "Detecting Derogatory Compounds – An Unsupervised Approach", in NAACL/HLT, 2019. 
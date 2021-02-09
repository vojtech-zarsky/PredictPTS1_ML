# PredictPTS1_ML
A script used to predict E. histolytica peroxisomal proteins. The file "pts1_candidates.amoebozoa.noEntamoeba.fasta" contains putative peroxisomal proteins with PTS1 from aother amoebozoans. E. invadens predicted proteome was used as a dataset of non-PTS1 proteins. By default uses 10 C-terminal amino acids. This can be changed in the script.


run:

python predictPTS1_ML.py train \<pts1file> \<non-pts1file>

python predictPTS1_ML.py predict \<ifile>


Creates a trainPts1ML.model.pickle file and an \<infile>.annotation.tsv table.

# PROJECT-7
Quality and Intelligibility for Anechoic Separation

SUBJECTIVE EVALUATION

QUALITY: 

Step 1:

Download PEASS toolKit from http://bass-db.gforge.inria.fr/peass/ and Grid Corpus files from http://spandh.dcs.shef.ac.uk/avlombard/

Step 2:

Mix them with a TIMIT file(acting as Masker). All source files are in "grid corpus clips" folder.

Step 3:

The mixtures are called "ANchors". Separate them by using MESSL, DUET, CMESSL, FRU, SONET (use gregnet90.mat and ipd90.mat to generate ILD and IPD masks respectively), EMSONET (use gregnet90.mat to generate ILD mask) source separation algorithms present in their respective folders present in this repository. All anchors, references (clean grid files), and Estimated targets are already stored in the "QUALITY TESTING FOLDER' present in this repository. 

Step 4:

The mixtures are evaluated subjectively by users using PEASS Tool Kit present in Project-7 (Quality and Intelligibility evaluation for Anechoic Separation.rar) folder in this repository. Follow the instructions given in its readme.txt document.

Step 5: 
Estimate the quality of the estimated target by comparing it with the Reference.wav files using the quality metrics given in the 'quality' and the "bss_eval" folders present in Project-7 (Quality and Intelligibility evaluation for Anechoic Separation.rar) folder in this repository.

 

INTELLIGIBILITY

Step1:

Send all files in INTELLIGIBILITY TESTING FOLDER present in Project-7 (Quality and Intelligibility evaluation for Anechoic Separation.rar) folder in this repository to listeners by email for subjective evaluation. These are the Estimated targets from all speech separation algorithms. The files must be accompanied by Excel sheet where the users can select the 'keywords' for each file. Add the scores for the correctly identified keywords.


Step2: 

Evaluate using objective metrics by using the programs in the "intelligibility" folder present in Project-7 (Quality and Intelligibility evaluation for Anechoic Separation.rar) folder in this repository.


Step3:

Evaluate the anchor and reference by using the following program.
Metrics_for_Ref_and_Anchors.m
PESQ_Eval_single_File.m
present in Project-7 (Quality and Intelligibility evaluation for Anechoic Separation.rar) folder in this repository

Cite As: Sania Gul, Muhammad Salman Khan, Néstor Becerra Yoma, Syed Waqar Shah,  Sheheryar: “Enhancing the correlation between the quality and intelligibility objective metrics with the subjective scores by shallow feed-forward neural network for time-frequency masking speech separation algorithms”, Applied Acoustics, Volume 188, 2022, 108539,

# Annotation of you-pronouns in Early Modern English texts using machine learning techniques
A project by Maria Irena Szawerna for the Machine learning for statistical NLP: Advanced LT2326 course at the University of Gothenburg.  

+ The final version of the project code: project-acc80-with-anns.ipynb. This file contains all of the code used for the project, and, in the final part, the results of it having been run (evaluation of one of the trained models).
+ The trained model with 80% accuracy corresponding to the aforementioned Notebook can be found under https://drive.google.com/file/d/19cgezyYmkCgzMmk0aROqyaAFi991ltsV/view?usp=sharing.
+ test_samples_full.pickle and train_samples_full.pickle are the sample splits that were used for training that model.
+ trimmed-as-you-like-it.txt and trimmed-hamlet.txt are the manually-annotated files that were used for training and evaluating the model.
+ macbeth.txt is the unannotated file that was then annotated using the trained model and saved under macbeth_annotated.txt
+ ML2_project_presentation.pdf contains the slides from the in-class project presentation.
+ project_report.pdf is the final project report.  

The project can be re-run as it is on mltgpu, simply run all the cells in the Notebook file, as long as you have the trimmed-as-you-like-it.txt and trimmed-hamlet.txt files in the same folder. If you want to play around with the model or the datasets that were used, you also need to put them in the same folder and then you can use the load functions to load them into the notebook. Please note that the trained model is too large to be included in the repository and the Google Drive link to it is in one of the points above.

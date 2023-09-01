# Alzheimers-Detection-Using-Handwriting
This is a notebook where I analyze the DAWRIN dataset to detect alzheimer's in an individuals handwriting. To classify, I used random forest in python.

# Background
  Alzheimer's is a type of dementia that effects memory, thinking, and behvior. It is caused by increasing age, and primarily affects people above the age of 65. As a person develops Alzheimer's, it progressively becomes worse where the individual can lose the ability to carry a conversation or even take care of themselves. After diagnosis, a person can expect to live on average between 4 to 8 years, but on better cases up to 20 years. Luckily there is medication to help slow the worsening of Alzheimer's, but nothing to completely prevent it from happening.
  
  The data used for the detection of Alzheimer's through handwriting comes from the DARWIN (Diagnosis AlzheimeR WIth haNdwriting) dataset. This dataset is made up of 174 individual's handwriting where roughly half are Alzheimer's patients (P), and healthy people (H). The handwriting was taken through tasks the individuals were asked to do, and then variables like time in air were measured. In doing so, the creators of the DARWIN dataset provided us the materials we need to use machine learning techniques to detect the early stages of Alzheimer's through handwriting. Some of the tasks recorded were connecting points through lines and copying phrases that were written in front of them, all of which test different parts of the brain.

  Using handwriting data, I will use a random forest classifier to predict whether an individual has Alzheimer's or not. The goal is for future handwriting data to be inserted and accurately predict the correct diagnosis, saving the individual time to get treatment to slow down the process.

### Data is taken from https://www.kaggle.com/datasets/taeefnajib/handwriting-data-to-detect-alzheimers-disease.

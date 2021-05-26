# Automated Vacancy Recommender
The aim of this project was to recommended top n resumes to the recruiter based to similarity between job description and resume/cv.

All the Resumes/Cv's are first preprocessed. Special characters, multi-white-spaces and single letter word are removed.
The dataset is split into the tokens and the preprocessing steps are applied on tokenized dataset such as stop word removal, case-folding, and lemmatization.

The features are extracted from the preprocessed data using the Tf-Idf. Specifically, we have calculated tf-idf (term frequency, and inverse document frequency) for each term present in our dataset.

The project has 2 models:
1) Classification Model which classifies Resumes/Cv's and Job Descriptions into right category.
2) Recommendation Model that recommended top n Resumes/Cv's based on similarity between job description and resume/cv using cosine similarity.


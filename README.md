# elmo-morphosyntactic-analysis
As a submission to Sigmorphon 2019 Task 2, we developed a machine learning model for predicting POS tags, Unimorph tags, and Lemma forms. We did this using elmo contextual word embeddings trained only on the bible in each language. We use the bible alignment to achieve cross-lingual transfer of vectors in a translation matrix.

Because I worked on this project with a team, and all of their code is their own, I have chosen to include only the data and code examples from the portion of the project with which I was involved.
This includes the processing of training data, the training of ELMo weight models, and the calculation of ELMo embedding vectors. The parts of the process that I did not write include the calculation of the translation matrix, the training of morpheme embeddings, and the lemmatizer, as well as the final script to read in test data for label prediction.

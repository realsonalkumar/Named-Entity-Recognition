# Named-Entity-Recognition
This repository discusses an approach for named entity recognition using sklearn-crf. This Machine Learning hackathon was conducted by Vaultedge Softwares. It is a second place approach.

Initially we tried a sequence-to-sequence deep learning model based in LSTM, GRU and word embeddings. However we lagged behind in the leaderboard even after repetitively fine tuning our model. We eventually moved to multinomial naive bayes and finally CRF which gave us the best results.

We converted individual words to complete sentences and the trained and tested the model and tuned hyper-parameters.

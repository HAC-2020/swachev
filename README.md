# swachev-
# Covid-19 Repo/Project Recommender

This repo contains an advanced recommender system for covid-19 projects based on language and keywords. This model is developed upon the already existing base model[1] with improved accuracy in recommendation using BERT Embedding[2]


# Setup Instructions
```
python3 -m venv covid19-repo-recommender
source covid19-repo-recommender/bin/activate
python3 -m pip install -r requirements.txt
python3 -m ipykernel install --user --name=covid19-repo-recommender
```
# Start MLFlow Server:
```mlflow server```

# References
```
[1]https://github.com/BookletAI/covid19-repo-recommender
[2]Reimers, N., & Gurevych, I. (2019). Sentence-bert: Sentence embeddings using siamese bert-networks. arXiv preprint arXiv:1908.10084.
```

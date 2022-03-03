# MLFlow POC
Sandbox for MLFlow proof of concept.

I tested MLFlow only with sklearn models and some basic functions:
- start_run(), active_run() and stop_run()
- log_model and load_model()
- evaluate()

Three models are created, saved and loaded locally in these notebooks:
- **vectorizer**: a sklearn pipeline that applies a TfIdfVectorizer.
- **clustering**: a sklearn AgglomerativeClustering that separates the reviews into clusters in a non-supervised and hierarquical way.
- **classifier**: a sklearn DecisionTreeClassifier being trained on top of the clusterized reviews.

My notes on MLFlow:
Easy to use and very valuable for ml projects.

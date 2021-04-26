Note à l'intention de l'évaluateur :
------------------------------------



1. Liste des fichiers du livrable:

	1.1. Notebooks jupyter (la numérotation des notebooks correspond à la chronologie du travail effectué) 

		P5_1_import_and_process_natural_text.ipynb
		P5_2_corpus_analysis.ipynb
		P5_3_topics_detection.ipynb
		P5_4_1_classification_from_bows.ipynb
		P5_4_2_classification_from_tf-idf.ipynb
		P5_4_3_classification_from_lda.ipynb
		P5_4_4_classification_from_nmf.ipynb
		P5_4_5_classification_from_lda_matrix.ipynb
		P5_4_6_baseline.ipynb
		P5_5_1_universal_sentence_encoder_DAN_4_tags.ipynb
		P5_5_2_universal_sentence_encoder_transformer_5_tags.ipynb
		P5_6_results.ipynb

	1.2. Répertoires du projet
	
		results/ : contient les résultats de chaque modèle de prédiction de tags
		model/ : contient les modèles de topics detection
		heroku_LR_tfidf/ : contient l'ensemble du projet de webapp de prédiction de tags sur heroku
		
		Le répertoire data/ contenant les données brutes, les features et différents modèles n'est pas fourni car trop imposant en taille (7go).

	1.3. Rapport et présentation :
	
		P5_rapport.pdf
		P5_presentation.pdf
	
	
2. Git

Seul le répertoire principal heroku_LR_tfidf/ sont versionnés sous Git et accessible sous Github sous le lien: "https://github.com/daidi06/Stackoverflow-Tags-Prediction-tfidf".


3. Webapp prédiction de tags : 

https://stackoverflow-tags-prediction.herokuapp.com/

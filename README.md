# Text-classification-of-Song-lyrics
Predict the Singer from text/lyrics

Here I build a text classification model on song lyrics. The aim is to predict the Singer from a piece of text/lyrics. For simplicity purpose only four singers with ten songs each were taken. Following things are done step by step.
+	Collection of lyrics dataset: Songs and corresponding singers are selected.
+	Four singers Ed Sheeren, Dua lipa, Michael Patrick Kelly and Rihanna are selected and ten random songs were chosen for Web scrapping from www.lyrics.com.
+	A CORPUS is constructed from the lyrics of all the songs and later cleaned.
+	Exploratory Data Analysis is done on the lyrics and Singer.
+	For modelling purpose, the text is converted to vector and then normalized.
+	Logistic Regression model is applied and few texts/lyrics are checked.	
+	The model is saved to a pickle file for future use.
+	The accuracy is checked by Naive Bayes, SGDClassifier and LogisticRegression.
+	Topic modelling is done to find relevant topics from the lyrics.
+	A ‘wordcloud’ is constructed to see the frequency of words appearing in the lyrics.

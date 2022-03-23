# Movie-Review-Sentiment-Classification-Using-TensorflowLite
--------------------------------------------------------------------

This is a end to end application on movie review sentiment classification built using TensorflowLite(Tiny ML) that categorizes a paragraph into predefined groups based on its content.

This pretrained model predicts if a paragraph's sentiment is positive or negative. It was trained on ***Large Movie Review Dataset v1.0*** from Mass et al, which consists of IMDB movie reviews labeled as either positive or negative.

This model was trained on movie reviews dataset so we may experience reduced accuracy when classifying text of other domains.

### Steps to classify a paragraph with the model 👎
----------------------------------------------------------------------------------------

  * Tokenize the paragraph and convert it to a list of word ids using a predefined vocabulary.
  * Feed the list to the TensorFlow Lite model.
  * Get the probability of the paragraph being positive or negative from the model outputs.


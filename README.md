# Entity-Recognition:

Named Entity Recognition is a branch of information extraction. This is used to identify entities such as "Organizations", "Person", "Date", "Country", etc. that are present in the text.

## Prerequisites

- Data preparation and model training workflows for entity extraction using arcgis.learn is based on spaCy & Hugging Face Transformers libraries. A user can choose an appropriate backbone to train the model.
- Refer to the section Install deep learning dependencies of `arcgis.learn` module for detailed explanation about deep learning dependencies.
- Labeled data: For EntityRecognizer to learn, it needs to see examples that have been labeled for all the custom categories that the model is expected to extract.

## Entity recognition with spaCy
This Model works on the Embed > Encode > Attend > Predict deep learning framework .

Embed: This is the process of turning text or sparse vectors into dense word embeddings. These embeddings are much easier to work with than other representations and do an excellent job of capturing semantic information. This is achieved by extracting word features using feature hashing[2] followed by a Multilayer Perceptron. A video description of this workflow can be found here.

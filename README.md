# Entity-Recognition

Named Entity Recognition is a branch of information extraction. This is used to identify entities such as "Organizations", "Person", "Date", "Country", etc. that are present in the text.

## Prerequisites

- Data preparation and model training workflows for entity extraction using arcgis.learn is based on spaCy & Hugging Face Transformers libraries. A user can choose an appropriate backbone to train the model.
- Refer to the section Install deep learning dependencies of `arcgis.learn` module for detailed explanation about deep learning dependencies.
- Labeled data: For EntityRecognizer to learn, it needs to see examples that have been labeled for all the custom categories that the model is expected to extract.

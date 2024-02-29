# Quote-Deidentification-using-Named-Entity-Recognition-with-spaCy
This project demonstrates how to use spaCy for Named Entity Recognition (NER) and deidentification of quotes.

The code is stored in the MyNamedEntityRecognition.ipynb file.

## Sections:

### Environment Preparation: 
This section installs and imports necessary packages, including spaCy, and loads the English language model (en_core_web_sm).

### Data Exploration:
A corpus of text passages containing quotes is provided. These passages will be used for NER and deidentification.

### Data Preparation and Anonymization: 
This section processes each text passage in the corpus. It first cleans the text by removing special characters. 
Then, it uses spaCy's NER to identify entities in the text. Entities labelled as "PERSON" are considered named entities (e.g., names of people) and are removed from the text, 
effectively anonymizing the quotes. The cleaned and anonymized text is stored in a new corpus (anonymized_corpus).

### Result:
The final output is the anonymized corpus, where quotes have been deidentified by removing named entities. 
This process is useful for anonymizing text data for privacy or security purposes while retaining the overall structure and meaning of the text.



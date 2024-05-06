# Legal-NER
Named entity recognition is a commonly studied problem in Natural Language Processing and many pre-trained models are publicly available. However legal documents have peculiar named entities like names of petitioner, respondent, court, statute, provision, precedents, etc. These entity types are not recognized by standard Named Entity Recognizers like Spacy. Hence, a Legal NER model and annotated datasets are needed for this task for Indian courts. Due to the peculiarity of Indian legal processes and terminologies, it is important to develop separate legal NER for Indian court judgment texts.
The following image shows the famous named entities in legal text.
![image](https://github.com/Anirudh2040/Legal-NER/assets/95646144/46f06292-c324-4c02-94ad-f9cfaa7377c2)

The code file is attached along with the datasets. You can change the path of files in the code accordingly. Everything is present in the code itself.
The Huggingface links for the pre-trained models used in this project are given below
1. InLegalBert - https://huggingface.co/law-ai/InLegalBERT
2. InCaseLawBert - https://huggingface.co/law-ai/InCaseLawBERT
3. CustomInLawBert - https://huggingface.co/law-ai/CustomInLawBERT


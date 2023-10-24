# Cyber-Bullying-Classifier-Bengali-Language
In recent years, the number of social networking sites has grown dramatically, providing a platform for individuals all over the world to connect and discuss their interests. Cyberbullying is defined as harassing or insulting a person by sending hurtful or threatening communications via internet communication. Cyberbullying is a serious threat to the victims' physical and mental health. A cyberbully detection system is proposed to recognize and classify cyberbullying using two different approach (until now, work in progress) over Bengali language.

### Two approaches are:
    - Support Vector Machine(SVM)
    - Bidirectional Encoder Representations from Transformers (BERT)
        * Bangla-BERT
        * BERT base model (uncased)
## Dataset: 
This dataset is used from kaggle. Here this dataset contains 5 categories of cyberbullying text data, the most common across social media. Every day, people go through this kind of bullying on social media, especially on Facebook. This dataset was built by web scraping on media platforms like  YouTube, Facebook, and Twitter. There is 6010 data evenly distributed among political, sexual, troll, threat, and neutral.
[Dataset Link](https://www.kaggle.com/datasets/moshiurrahmanfaisal/bangla-cyber-bullying-dataset)

## Performance Analysis:
    Accuracy:
        - For SVM model: 64.33%
        - For Bangla-BERT model (Pretrained): 75.49%
        - For BERT-based-uncased model (Pretrained): 61.67%

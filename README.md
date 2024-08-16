# FakeeX

# Problem Definition
Develop a machine learning program to identify when a news source may be producing fake news. We aim to use a corpus of labeled real and fake news articles to build a classifier that can make decisions about information based on the content from the corpus. The model will focus on identifying fake news sources, based on multiple articles originating from a source. Once a source is labeled as a producer of fake news, we can predict with high confidence that any future articles from that source will also be fake news. Focusing on sources widens our article misclassification tolerance because we will have multiple data points coming from each source.

The intended application of the project is for use in applying visibility weights in social media. Using weights produced by this model, social networks can make stories that are highly likely to be fake news less visible.

Planning: -

Data Collection  
Model Building  
Backend work  
Deployment  

Enter your text or generate a random one from our dataset to try it.

The text is first preprocessed and transformed as a vector. Then, the transformed vector is feeded to the trained model to be classified as fake or not fake.

## Start Project

Follow these commands to start your project.

```bash
pip install -r requirements.txt
```
```bash
python app.py
```

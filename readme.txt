INTRODUCTION

In recent years, due to the booming development of online social networks, fake news for various 
commercial and political purposes has been appearing in large numbers and widespread in the online 
world. With deceptive words, online social network users can get infected by these online fake news easily, 
which has brought about tremendous effects on the offline society already.

In today’s digital landscape, misinformation spreads like wildfire. False narratives, misleading headlines, and 
fabricated stories infiltrate social media platforms, eroding public trust in reliable sources. The consequences are
profound, affecting individual decision-making, public opinion, and even political landscapes.

Fake news isn’t a monolithic entity; it wears various disguises:
1. Clickbait Articles: Sensational headlines lure readers, leading to clicks and ad revenue.
2. Propaganda and Disinformation: Malicious actors intentionally spread false narratives to manipulate 
public sentiment.
3. Satirical Content: Sometimes, humor or satire is misconstrued as factual news.
4. Confirmation Bias: Consumers tend to believe information that aligns with their existing beliefs.

An important goal in improving the trustworthiness of information in online social networks is to identify 
the fake news timely. This aims at investigating the principles, methodologies and algorithms for detecting 
fake news articles, creators and subjects from online social networks and evaluating the corresponding 
performance.

Machine learning offers a powerful solution to combat misinformation. By analyzing patterns, identifying 
features, and learning from data, we can develop models capable of flagging suspicious content. Our 
focus lies on the Passive-Aggressive Classifier (PAC), an algorithm that adapts to changing data and 
provides accurate predictions.

Passive-Aggressive Classifier

Passive Aggressive algorithms are online learning algorithms. Such an algorithm remains passive for 
a correct classification outcome, and turns aggressive in the event of a miscalculation, updating and 
adjusting. Unlike most other algorithms, it does not converge. Its purpose is to make updates that 
correct the loss, causing very little change in the norm of the weight vector.

Passive: If the prediction is correct, keep the model and do not make any changes. i.e., the data in the example 
is not enough to cause any changes in the model.

Aggressive: If the prediction is incorrect, make changes to the model. i.e., some change to the model 
may correct it.

Tf-idf Vectorizer
 TF (Term Frequency): The number of times a word appears in a document is its Term Frequency. A 
higher value means a term appears more often than others, and so, the document is a good match when the 
term is part of the search terms.
 IDF (Inverse Document Frequency): Words that occur many times a document, but also occur many times in 
many others, may be irrelevant. IDF is a measure of how significant a term is in the entire corpus.
The TfidfVectorizer converts a collection of raw documents into a matrix of TF-IDF features.

# BEmoC Dataset Experiments

| Model Name   | Techniques                           | Accuracy |
|--------------|--------------------------------------|----------|
| BanglaBERT   | cleanTEXT                            | 72%      |
| BanglaBERT   | cleanTEXT, 121 stopwords             | 70%      |
| BanglaBERT   | 121 stopwords                        | 68%      |
| BanglaBERT   | cleanTEXT, 89 stopwords, tf-idf      | 68%      |
| BanglaBERT   | cleanTEXT, 89 stopwords               | 71%      |
| BanglaBERT   | cleanTEXT, 81 stopwords               | 69%      |
| BanglaBERT   | cleanTEXT, oversampling               | 73%      |
| BanglaBERT   | lemmatization                        | 67%      |
| XLM-RoBERTa  | lemmatization                        | 66%      |
| BanglaBERT   | cleanTEXT, tf-idf, le=2e^-5      | 70%      |
| BanglaBERT   | cleanTEXT, tf-idf, le=1e^-5       | 71%      |

## Notes:
- "Model Name" denotes the name of the model used.
- "Techniques" lists the preprocessing techniques applied to the data.
- "Accuracy" represents the achieved accuracy on the BEmoC dataset.

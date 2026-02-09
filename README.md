# AIG 230 – Lab 04  
## Word Embeddings: Learning Meaning from Context

Working with:

- **Gensim** for training Word2Vec and FastText models  
- **scikit-learn** for dataset loading and dimensionality reduction  
- **NLTK** for basic tokenization and preprocessing  
- **matplotlib** for visualization  

---

Using the 20 Newsgroups dataset, I did a comparison of Word2Vec and FastText using the target word "space" to determine the differences between the top 10 neighbors and their prediction scores given windos of 2 and 10.
I also varied the vector size from 50 to 100 to 200.

In addition, I used CBOW and Skip-gram for another set of comparisons using the same corpus.
I also used bigrams using gensim.models.Phrases to determine the difference before and after training




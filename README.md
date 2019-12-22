# ml-msk-cancer

Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment

## Classifying clinically actionable genetic mutations

A lot has been said during the past several years about how precision medicine and, more concretely, how genetic testing is going to disrupt the way diseases like cancer are treated.
<p>Once sequenced, a cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers). 
Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature.
<p>Using the knowledge base, this algorithm tries to classify genetic variations.
<p>I have used Logistic Regression method and predicted probabilistic values for the each of the classes. TFIDF vectorization is used for the encoding of text to numerical vectors. Tried with varying 1-gram, 2-gram, etc., and varying max_feature count. And got a log-loss of 0.41 for train dataset. (Train is 70% of stratified sample of the total dataset) .

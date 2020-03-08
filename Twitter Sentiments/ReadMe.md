This project is aiming to analyze how travelers in February 2015 expressed their feelings on
Twitter, through creating and tuning an ULMFiT model to correctly classify Twitter airline
sentiment data. The results produce 1 of 3 sentiments (positive, negative, and neutral).
The tweets are quantifiable through tokenization to create a numeric representation of words. I
used a language model provided from the fast.ai library by applying the pre-calculated
weights. It providez a word embedding scheme that aligns with the corpus of airline tweets. In
order to capture the meaning in each word, the language model hyperparameters are tuned
and it will lead to a sentiment result. If the model is accurate, my result will match the prelabeled
sentiment. 

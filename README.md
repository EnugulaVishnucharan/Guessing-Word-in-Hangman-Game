# Guessing-Word-in-Hangman-Game 
BERT tries to predict the masked word in a sentence.Here words are tokens. But in our case letters are tokens and we have to predict masked letter. 
Fine-tuning it on our specific task of letter prediction ensures that the model can influence its contextual understanding at a finer granularity. Used bert-base-uncased model (It is uncased i,e it treats Hangman and hangman as same). Even  upper case letter it treats same as in case of lower letter .

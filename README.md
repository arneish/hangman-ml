# hangman-ml
A language-model(n-gram) based Hangman player trained on a corpus of 250,000 words. 
Performance evaluated on a test-set (mutually exclusive of the training corpus) against a baseline algorithm that makes predictions based on statistical similarity of a test word to words in the training corpus. Boost in performance is primarily due to context capture in an n-gram model, absent in the baseline.

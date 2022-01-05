# Understand and implement TF-IDF, PMI and Entropy calculations on documents

### Tasks Performed:
1. Term Frequency (TF): tf(i,j) = (term 'i' in doc 'j') / (total words in doc 'j')

2. Inverse Document Frequency (IDF): idf(i, J) = log(total documents(J) /documents with term 'i')

3. TF-IDF: tf(i, j) * idf(i, J)

4. PMI: It measures how much more likely the words co-occur than if they were independent in the text. It is calculated as: PMI(word1, word2) = Probability(word1, word2)/ Prob(word1) P(Word2)

5. Entropy: Is defined as the sum of the probability of each label times the log probability of that same label -> H(A) = -sum(p * log(p))

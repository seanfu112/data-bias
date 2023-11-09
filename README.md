#Coding Assignment: Data Bias

###Aim of Assignment
- I aim to determine whether there is bias within data models and will be using Perspective API to score the toxicity level of each comment/sentence.

###Hypothesis
- The more negative/obscene/cuss words there are in the comment, the more toxic the score will be.
- *In this study, Sentence A will be less negative while Sentence B will be more negative

###Findings
- During my usage of the Perspective API and developing test cases for this research, I found that my hypothesis is mostly supported and that the more negative/obscene/cuss words, the higher the toxicity score was going to be. However, my results were a mix of success and challenges. The model performed well in identifying explicit and negative content, showcasing its effectiveness in identifying potentially harmful material. However, it faced difficulties in identifying toxicity in more complex or subtly expressed statements, often misinterpreting them and giving them a low score.

- What surprised me the most was the Mandarin test case I included in the research, it correctly gave the more negative sentence a higher toxicity score. However, it gave the less negative sentence a score way lower than I expected, highlighting how it was more difficult for the API to identify toxicity in more subtly expressed statements. 

- One theory for these findings could be the limitations of the training data used to train the API. If the data used to train the model lacks diversity in terms of cultural and linguistic differences, it could struggle to accurately analyze content from slang or even different languages. Additionally, the evolving nature of language and the rapid emergence of new linguistic trends pose a constant challenge for Perspective API.


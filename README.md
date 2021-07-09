# Natural-Language-Processing

 I made this personal project involving natural language processing in order to learn more about the different aspects of nlp, such as Sentiment Analysis as well as Entity Recognition. This type of language analysis would be helpful in future projects that center around automated interactions with humans, or even sentiment anaylsis of social media. 
 
 #How to use
 To use, first download the Stanford CoreNLP package from https://stanfordnlp.github.io/CoreNLP/. 
 Next, you will likely want to use an IDE, preferably IntelliJ IDEA, and download the files from GitHub as well as the Stanford CoreNLP files. Create a new project with the Github files.
 To change the sentence being analyzed, change the words that are in quotations in the active files, which perform each aspect of NLP. Then, run the intended file and use the console to see the results. 
 
 | File/directory            | Purpose |
| --------------            | ------- |
| ```Lemma.java```          | Provides base/root word of each word in the provided sentence |
| ```README.md```           | This file with basic pointers to more information. |
| ```NER.java```               | Named Entity Recognition, recognizes and states which words are proper nouns, and what type (e.g. Person, State or Pronvince, etc.) |
| ```POS.java```    | Parts of Speech, Labels each word and punctuation of a sentence with abbreviations whose meanings can be found in info_pos. E.g. NNS(Plural Noun), JJ(Adjective), etc. |
| ```Pipeline.java```                | Uses the Stanford CoreNLP files provided to run the written programs to produce the outputs. |
| ```SentenceRecognizer.java```               | Splits a block of text into each separate sentence. |
| ```SentimentAnalysis.java```                | Recognizes and states overall sentiment of a sentence (e.g. Neutral, Positive, Negative) |
| ```Tokenize.java```     | Splits sentence into each individual word. |
| ```info_pos```     | Contains meanings for abbreviations produced by POS.java |

Credit for Tutorial: Dinesh Krishman https://idineshkrishnan.com/

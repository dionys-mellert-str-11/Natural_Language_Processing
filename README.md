# Natural Language Processing

What is Natural Language Processing (NLP) ? <br>
It is a subject of Artificial Intelligence that is focused in giving a computer the ability to process, understand and learn from text. <br>

What are the terms normally used in NLP ? <br>
1. Corpus, Tokens, and Engrams <br>
  - Corpus can be define as a collection of structured text in written or spoken form. <br>
  - Tokens is an instance of a sequence of characters in some particular document that are grouped together as a useful semantic unit for processing, for example: never give up. <br>
  - Engrams, using "never give up" as an example <br>
    * uni-grams (n=1), never, give, up (it represents one word). <br>
    * di-grams (n=2), never give, give up (it represents 2 words together). <br>
    * tri-grams (n=3), never give up (it represents 3 words together). <br>
2. Tokenization <br>
  - Tokenization is used to split paragraphs and sentences into smaller units that can be more easily assigned meaning, using previous example: 3 tokens – Never-give-up. Tokenization can be categorized into 2: white-space tokenization and regular expression tokenization. <br>
    * white-space tokenization, text is split into words by splitting them from white spaces. <br>
      - for example: "my home address is Dionys-Mellert-Strasse" <br>
      - it will be splitted into following tokens: "my", "home", "address", "is", "Dionys-Mellert-Strasse" <br>
      - remark: "Dionys-Mellert-Strasse" is not split because the tokenization process was based on whitespaces only <br>
    * regular expression tokenization, it splits a string into substrings using a regular expression <br>
      - for example: "Good sausagges cost €3.5\nin Frankfurt. <br>
      - it will be splitted into following tokens: "Good", "saussages", "cost", €3.5", "in", "Frankfurt", "." <br>

3. Normalization
   - Normalization is a process of converting a token into its base form. <br>
   - for example: He visited Germany, he visited Germany, HE VISITED GERMANY, hE ViSiTeD GERmany <br>
   - the output of normalization will be: he visited Germany <br>
   
4. Stemming
   - It is a a technique used to reduce an inflected word down to its word stem. <br>
   - for example: creative, creation, created, creates, creating <br>
   - the output of the stemming will be: create <br>
   
5. Lemmatization
   - It is a process to reduce words to their base form, also known as the root form. <br>
   - for example: runs, running, ran <br>
   - the output of the stemming will be: run <br>

What are the examples of real world projects based on NLP ? <br>
1. Sentiment analysis: <br>
   - a model that can predict a sentiment of a piece of text, such as whether it is positive, negative, or neutral. <br>
   - This can be used for a variety of purposes, such as customer sentiment analysis or social media monitoring. <br>

2. Text classification: <br>
   - a model that can classify text into different categories, such as news articles, product reviews, or emails. <br
   - This can be used for a variety of purposes, such as email filtering or product recommendation. <br>

3. Named entity recognition: <br>
   - a model that can identify named entities in text, such as people, places, or organizations. <br>
   - This can be used for a variety of purposes, such as search engine ranking or product recommendation. <br>

4. Machine translation: <br>
   - a model that can translate text from one language to another. <br>
   - This can be used for a variety of purposes, such as providing real-time translation for tourists or translating documents for businesses. <br>

5. Text summarization: <br>
    - a model that can summarize a piece of text into a shorter, more concise version. <br>
    - This can be used for a variety of purposes, such as providing summaries of news articles or generating summaries of customer reviews. <br>

What are Python Libraries available for NLP ? <br>
NLTK, Spacy, Gensim, CoreNLP, Polyglot, TextBlob, Regular Expreseion, Wordcloud, AllnNLP, etc. <br>


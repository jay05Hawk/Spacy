# Spacy
Advance in  NLP Library

# What's spaCy?

SpaCy is **free**, **open-source library** for advanced **Natural language processing**(NLP) in Python.

Suppose you're working with a lot of text, you'll eventually want to know more about it. For example, what's it about? What does the words mean in the context? Who is doing what to whom? What products and compnaies are mentioned in the text? Which texts are simmilar to each other.

spaCy is designed specifically for **production use** and helps you build applications that process and "understand" large volume of text. It can be used to build **information extraction** or **natural language processing** systems, or to pre-process text for **deep learning**.


## Features

Here, you'll come across mentions of spaCy's features and capabilities. 

### Statistical models

Some of spaCy's features works independently, other requires statistical models to be loaded, which enable spaCy to **predict**
linguistic annotations-For example, whether a word is a verb or noun. spaCy currently offers statistical models for a variety of languages, which can be installed as individual Python modules. Models can differ in size, speed, memory usage, accuracy, and the data they include. The model you choose always depends upon your use cases and the texts you're working with. For a general use case, the small and the default models are always a good start. They typically include the following components:

  - **Binary weights** for the part-of-speech tagger, dependency parser and named entity recognizer to predict those    annotations in context.
  
  - **Lexical entries** in the vocabulary, i.e. words and their context-independent attributes like the shape or spelling.
  
  - **Data files** like lemmatization rules and lookup tables.
  - **Word vectors**,  i.e. multi-dimensional meaning representations of words that let you determine how similar they are to each other.
  - **Configuration** options, like the language and processing pipeline settings, to put spaCy in the correct state when you load in the model.
  
  ### Linguistic annotations

spaCy provides a variety of linguistic annotations to give you **insights into a text’s grammatical structure.** This includes the word types, like the parts of speech, and how the words are related to each other. For example, if you’re analyzing text, it makes a huge difference whether a noun is the subject of a sentence, or the object – or whether “google” is used as a verb, or refers to the website or company in a specific context.


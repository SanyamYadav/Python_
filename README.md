
In this project, I have used Python2 and NLTK to construct a system that reads simple facts and then answers questions about them. 

You can think of it as a simple form of both machine reading and question answering.

There are different parts to the system.

**pos_tagging.py** is concerned with part-of- speech tagging of questions, allowing for ambiguity and also taking account of singular and plural forms for nouns and verbs. 

**semantics.py** 
is also given a context free grammar for the question language, along with a parser, courtesy of NLTK. was to write some Python code that does agreement checking on the resulting parse trees, in order to recognize that e.g. Which ducks flies? is ungrammatical. 


**agreement.py**: Agreement checking is used in the system to eliminate certain impossible parse trees. In Part D, you will give a semantics for questions, in the form of a Python function that translates them into lambda expressions.

# OpenDomainQA

## Study on Open Domain Question Answering
***
A question answering implementation may construct its answers by querying a structured database of knowledge or information, usually a knowledge base. More commonly, question answering systems can pull answers from an unstructured collection of natural language documents.

Some examples of natural language document collections used for question answering systems include:

- a local collection of reference texts
- internal organization documents and web pages
- compiled newswire reports
- a set of Wikipedia pages
- a subset of World Wide Web pages

Question answering research attempts to deal with a wide range of question types including: fact, list, definition, How, Why, hypothetical, semantically constrained, and cross-lingual questions.

__Closed-domain question answering__ deals with questions under a specific domain (for example, medicine or automotive maintenance), and can exploit domain-specific knowledge frequently formalized in ontologies. Alternatively, closed-domain might refer to a situation where only a limited type of questions are accepted, such as questions asking for descriptive rather than procedural information. Question answering systems in the context of machine reading applications have also been constructed in the medical domain, for instance related to Alzheimer's disease

__Open-domain question answering__ deals with questions about nearly anything, and can only rely on general ontologies and world knowledge. On the other hand, these systems usually have much more data available from which to extract the answer.

## Factoid vs Non Factoid__

__Factoid__

These are questions that “can be answered with simple facts expressed in short text answers”; usually, their answers include “short strings expressing a personal name, temporal expression, or location” (Jurafsky and Martin, 2017). 

An example of a factoid question and its answer is

Q: Who is Canada’s prime minister?
A: Justin Trudeau.

***

__Non Factoid__

Non-factoid questions ask for “opinions, suggestions, interpretations. Answering and evaluating the quality of the provided answers for non-factoid questions have proved to be non-trivial due to the difficulty of the task complexity as well as the lack of training data. To address the latter issue, numerous researchers have tried to take advantage of
user-generated content on Community Question Answering (CQA) web sites such as 
- Yahoo! Answers
- Stack Overflow
- Quora

These web forums allow users to post their own questions, answer others’ questions, comment on others’ replies, and upvote or downvote answers. __Our dataset is one of its type where we use Reddit QA__

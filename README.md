# KDRE: Robust Cross-lingual Knowledge Base Question Answering via Knowledge Distillation 
All of these documents are data which used in the study "Robust Cross-lingual Knowledge Base Question Answering via Knowledge Distillation"
These documents contains the following files:
* original questions of the dataset SimpleQuestions
* backtranslated train questions of SimpleQuestions
* translated test questions of SimpleQuestions

# Original questions
All the questions drieved from the standard dataset SimpleQuestions are included in this file.
The English questinons are writed by workers of crowdsourcing.

See more details about dataset SimpleQuestions in:
         Bordes, A., Usunier, N., Chopra, S., & Weston, J. (2015). Large-scale simple question answering with memory networks. arXiv preprint arXiv:1506.02075.
         
# Translated questions 
This file mainly contains the back translated training questions and the translated testing questions.
Back translation means the English questions are first translated to other different languages, and then are translated to English.
The back translated questions are used in the training procedure by the student model.
Then the English questions in the test set are translated to different languages which are used in the test procedure by the student model.

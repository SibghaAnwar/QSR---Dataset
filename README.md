# QSR---Dataset

Read me:

The data presented in this article is from Cornell Movie Dialogue Corpus. 
The Cornell Movie data consist of 617 movies having 269633 sentences and 10,292 conversation pairs [1].
Users in this dataset are movie characters. We take user index from the original data release as the user name.
Conversations are indexed by the id of the first utterance that make the conversation. 
This data is also related to the research paper entitle “Chameleons in imagined conversations: a new approach to understanding coordination of linguistic style in dialogs” [2].The raw data used is described and provided here.
In addition, this data will encourage research artificial intelligence (AI) based interacting agents to make them relaistic.
After Preprcessing of Raw movie scripts we have 3 csv file named as ( movies_lines, Network Creation , Basic Labelling, Subtpes Labelling)

# Network Creation:
        In this file we create a pairwise network of characters in which we have all pairs of chararcters with their conversational dailouges.

# Basic Labelling:
        In this file we have 3 columns and 3115 rows: 
        1st column, represents the conversations text. 
        2nd column, we label the behavior of agents ( mutualism, traditional, cooperative, opportunistic)
        3rd column, we represents the labels of basic relationships 4 (family, friend , pleasant and unpleasant)

# Subtpes Labelling:
In this file we have 3 columns and 3115 rows:
        1st column, represents the conversations text. 
        2nd column, we represents the labels of basic relationships 4 (family, friend , pleasant and unpleasant)
        3rd column, we represnt the 8 relationship subtypes (Consanguine, Annoying Acquaintance, Superficial Acquaintance,
                                                            Mentoring, Conjugal, Diverse Work, Undesirable, 
                                                            Close Acquaintance)

# Reference to a dataset:
[1] [Dataset] https://zissou.infosci.cornell.edu/convokit/documentation/movie.html conversations and metadata (IMDB rating, genre, character gender, etc.) from movie scripts (first release 2011).
Reference to a journal publication: 
[2] C. Danescu-Niculescu-Mizil, L. Lee, Chameleons in imagined conversations: A new approach to understanding coordination of linguistic style in dialogs, in: Proceedings of the 2nd Workshop on Cognitive Modeling and Computational Linguistic s, Association for Computational Linguistics, 2011, pp. 76–87.

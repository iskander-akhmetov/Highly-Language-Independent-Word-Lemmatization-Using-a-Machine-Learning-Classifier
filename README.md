# Highly-Language-Independent-Word-Lemmatization-Using-a-Machine-Learning-Classifier
Highly Language-Independent Word Lemmatization Using a Machine-Learning Classifier

In short, we train a RandomForest multiclass-multiputput Classifier on lemma-wordform wordpairs encoded by character embeddings obtained from the charcter cooccurrence matrix and test this approach on 25 languages. We compared our results with UDPipe (http://ufal.mff.cuni.cz/udpipe).

The dictionaries for 23 languages were taken from https://github.com/michmech/lemmatization-lists for which we thank Michal Měchura a lot! Russian dictionary source is http://odict.ru and for Turkish it is Zargan dictionary

The method is fully described in the article https://www.cys.cic.ipn.mx/ojs/index.php/CyS/article/view/3775.

It would be nice if you cite our article as:

@ARTICLE {iskanderakhmetovalexandrpakirinaualiyevaalexandergelbukh2020,
    author  = "Iskander Akhmetov, Alexandr Pak, Irina Ualiyeva, Alexander Gelbukh",
    title   = "Highly Language-Independent Word Lemmatization Using a Machine-Learning Classifier",
    journal = "Computacion y Sistemas",
    year    = "2020",
    volume  = "24",
    number  = "3",
    pages   = "1353-1364",
    month   = "sep"
}

# NLP_gutemberg_epidemia
consolidating databases for a future NLP project

## STEP1: database
I have extracted (by scrapping) and consolidated a database with all the french books and their text (.txt file) from the gutenberg project free library.  
https://www.gutenberg.org/browse/languages/fr  
The csv file is available on my github with the following metrics that have been extracted:  
- 4117 ebooks
- 1474 authors
- 22 authors have more than 20 books in the database like Sand, Dumas, Verne, Maupassant, Zola, Hugo, Daudet
- authors birth year ranges from 56 to 1954 with a median in 1825
- authors death year ranges from 104 to 1985 with a median in 1887
- the distribution of books per century is as followed. A majority of books from the XIXth century:  
    1st  :      3  
    15th :      8  
    16th :     68  
    17th :     81  
    18th :    214  
    19th :   2539  
    20th :    214 

## STEP2: have fun!  
I have plenty ideas to use this like these ones:  
- look for the books that relate to an epidemy and extract the paragraphs to build an anthology of epidemy wordings
    - all the tools have been built to extract all the sentences that contain a given word in a writer 'library'
    - 2 examples have been saved for the word 'épidémie' in the books from Emile Zola et from Jules Verne
- build a language models based on jules verne books  (statistical trigrams)
    - this has been done with books from Verne, Zola, Hugo, Maupassant, Proust
    - the language models are used for a "haiku" generator: you give 6 words and the system generates haikus almost publishable of the 5 authors  
    '''EXAMPLE:
    Emile Zola: la lune , semée d'abeilles , mouvant rideau / un bonheur infini à trouver un lit / la joie discrète ; cette fois  
    Jules Verne: la lune venait de tout navire / un bonheur providentiel / la joie de ces arbres sous ce feuillage spécial  
    Guy de Maupassant: la lune versait une lumière molle / un bonheur nouveau avait commencé / la joie de me déchirer  
    Marcel Proust: la lune pleurait et je pouvais m'approcher / un bonheur que j'eusse pu le faire / la joie d'être seul  '''
    
- build a free french books recommander system (not started)  

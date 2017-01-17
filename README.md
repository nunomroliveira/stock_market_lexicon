stock_market_lexicon
======================

Stock Market Lexicon

Opinion Lexicon adapted to stock market conversations in microblogging services (e.g., StockTwits, Twitter). This lexical resource was automatically created using diverse statistical measures and a large set of labeled messages from StockTwits.

The attributes of the lexicon are:
- Item: lexical item, either an unigram or a bigram.
- POS: Part of Speech (POS) tag
- Aff_Score: Sentiment score in affirmative (i.e., non-negated) contexts. 
- Neg_Score: Sentiment score in negated contexts.

The applied POS tags are based on the Penn Treebank POS tagset:
- $: Dollar sign 
- CC: Coordinating conjunction    
- CD: Cardinal number   
- DT: Determiner    
- EX: Existencial there
- FW: Foreign word    
- IN: Preposition or subordinating conjunction    
- JJ: Adjective
- LS: List item marker
- MD: Modal
- NN: Noun
- PD: Predeterminer
- PO: Possessive ending
- PR: Personal Pronoun 
- RB: Adverb
- RP: Particle
- SY: Symbol (mathematical or scientific)
- TO: to
- UH: Interjection
- VB: Verb
- WD: wh-determiner
- WP: wh-pronoun
- WR: wh-adverb

We added two more tags:
- null: bigram
- EM: Emoticons    

Citation Request:

Please include this citation if you use this lexicon resource: 

Oliveira, Nuno, Paulo Cortez, and Nelson Areal. "Stock market sentiment lexicon acquisition using microblogging data and statistical measures." Decision Support Systems 85 (2016): 62-73.

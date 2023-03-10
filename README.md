# syntactic-Tree-generator
The assignment consists in the development, in NLTK, OpenNLP, SketchEngine or GATE/Annie a pipeline that, starting from a text in input, in a given language (English, French,  German and Italian) outputs the syntactic tree of the sentence itself, intended as a tree with root in S for sentence, and leaves on the tokens labelled with a single Part-of-speech.

The tree is generated with a **PURE SYMBOLIC** approach by a LR analysis with CF LL2 grammar as a base. Candidates can assume the following:

    a) Adjectives in English and German shall be only prefixed to nouns, whilst in French and Italian are only suffixed;
    
    b) Verbs are all at present tense;

    c) No pronouns are admitted;

    d) Only one adverb is admitted, always post-poned with respect to the verb (independently of the language, and the type of adverb);


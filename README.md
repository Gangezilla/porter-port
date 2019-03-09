# porter-port

I've been doing quite a bit of learning about information retrieval lately, and wanted to understand better how a stemmer worked. 
I did some digging and was looking into the existing port of the Porter stemming algorithm, but found it a bit difficult to follow (https://tartarus.org/martin/PorterStemmer/js.txt), so decided to rewrite it.
It's definitely not perfect and could do with a bit of further cleaning, but it's hopefully a bit easier to read than the above implementation, which was my goal!

This is the original paper that was written by Martin Porter, https://tartarus.org/martin/PorterStemmer/def.txt. 
Going through the individual steps here and then following them in the paper makes it all make quite a bit more sense. 

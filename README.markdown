Overview
--------
eporter is a repackaged version of Alden Dima's erlang implementation of the
porter stemming algorithm from [here](http://tartarus.org/~martin/PorterStemmer).

Installation
------------
    git clone git://github.com/dweldon/eporter.git
    cd eporter && make

Interface
---------
### Functions
* eporter:stem(String)
* eporter:stem_file(InputFile, OutputFile)

### Example
    > eporter:stem("musical").
    "music"

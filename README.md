As a lexicon, for completeness, [WordNet][] [lexicographer files][] do contain obscene terms. Thus the database (dict) files generated out of these would also contain those terms. This project is to filter out such terms from those files and to maintain a lexicon database that is safe for usage in schools.

Using these files with [Artha][] is simple. Instead of having the default `dict/` directory, the `dict/` directory present here should be used. Artha will no longer show obscene terms in its search results.

No change of Artha's code or application file structure is required.

[WordNet]: http://wordnet.princeton.edu/
[lexicographer files]: http://wordnetcode.princeton.edu/wn3.1.dict.tar.gz
[Artha]: http://artha.sourceforge.net/

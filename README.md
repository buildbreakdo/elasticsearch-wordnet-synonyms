# Wordnet Synonyms for Elasticsearch Filter
WordNet synonyms
Synonyms based on WordNet format can be declared using format:

```
{
    "filter" : {
        "synonym" : {
            "type" : "synonym",
            "format" : "wordnet",
            "synonyms" : [
                "s(100000001,1,'abstain',v,1,0).",
                "s(100000001,2,'refrain',v,1,0).",
                "s(100000001,3,'desist',v,1,0)."
            ]
        }
    }
}
```

https://www.elastic.co/guide/en/elasticsearch/reference/2.4/analysis-synonym-tokenfilter.html

http://wordnetcode.princeton.edu/3.0/WNprolog-3.0.tar.gz

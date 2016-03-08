This project contains tools for working with SKOS-XL files such as those created by Smartlogic's Semaphore ontology editor tool.

The core XQuery functions can be found in /modules/skos-xl-util.xqy.

Sample ontology files can be found in /data/ontologies

Typical use is to pass the URI of the ontology as a parameter to a function.  For example to get a count of the concepts use:

```
s:count-concepts($ontology-uri)
```

Please let me know if you have any suggestions for other functions.


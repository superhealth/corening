#初识ES

##ES对应Mysql

| mysql  | ES       |
| ------ | :------- |
| schema | index    |
| table  | type     |
| row    | document |
| column | field    |

## TFIDF评分机制

Apache Lucene使用TF/IDF(term frequency/inverse document frequency，词频/逆向文档频率)评分机制

$Score=TF*IDF$

$TF(t in d)   =  	frequency½​$

$IDF(t)  =  1 +log(\frac{numDocs}{docFreq+1})​$


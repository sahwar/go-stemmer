# go-stemmer

[![Build Status](https://travis-ci.com/aquilax/go-stemmer.svg?branch=master)](https://travis-ci.com/aquilax/go-stemmer) [![GoDoc](https://godoc.org/github.com/aquilax/go-stemmer?status.svg)](https://godoc.org/github.com/aquilax/go-stemmer)

Bulgarian language stemmer library in go.

Uses rules from [BULSTEM](http://lml.bas.bg/~nakov/bulstem/).
Download the stemming rules and convert them to utf8 using iconv;

```
iconv -f cp1251 -t utf8 stem_rules_context_1.txt > stem_rules_context_1.utf8.txt
```
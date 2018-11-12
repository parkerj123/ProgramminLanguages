# String Rewriting Exercise

#### Rewrite Rules
```go
ab -> ba
ba -> ab
aa -> 
b -> 
```

Strings to Rewrite :


* abba:
```
-> baba
-> baab
-> bb
-> b
-> b
```



* bababa:
```
-> abbaba
-> abbbaa
-> abbb
-> abb
-> ab
-> ba
...
```

This ARS would be terminating if there was a measure function

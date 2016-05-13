---
layout: default
title: example-title
---

This page is written in [Markdown](http://packetlife.net/media/library/16/Markdown.pdf).

```Java
import Document from udapi.core.document;
import cz.ufal.udapi.core.impl.DefaultDocument;
Document doc = new DefaultDocument();
doc = new CoNLLUReader("test.conllu").readDocument();
```

```Perl
use Udapi::Core::Document;
my $doc = Udapi::Core::Document->new();
$doc->load_conllu('test.conllu');
```

```Python
import Document from udapi.core.document
doc = Document()
doc.load({'filename':'test.conllu'}) 
```

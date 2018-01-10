
lipu nimi
=========

Toki pona word dictionaries.

These dictionary files are collected and edited by me (agj), and represent my own interpretation of the language, which may be different from its author Sonja Lang's or its other speakers'.


## Files

These are 'tab-separated value' files, which means that each line is a row, and columns are separated by a tab character. Empty lines are also used for increased readability.

### english.tsv

Lists English keywords for toki pona words. The focus of these keywords is on conciseness rather than thoroughness. Whenever possible and sensible, a single English word is used per entry. Multiple entries for a single word identify different uses according to part of speech. Sometimes multiple keywords are used for the same part of speech, when multiple often-used meanings cannot be conveyed by a single English concept. Verbs are preceded by 'to' in order to make them explicit (except for the case of 'can').

```
toki pona word | part of speech | English keyword
```

Part of speech key:

- **n:** noun
- **mod:** modifier (adjective or adverb)
- **sep:** separator
- **vt:** transitive verb, used after _e_
- **vi:** intransitive verb
- **interj:** interjection
- **prep:** preposition
- **conj:** conjunction
- **kama:** compound verb preceded by _kama_
- **cont:** context word, used before _la_
- **oth:** other

### pu-status.tsv

Describes how words are treated in the official toki pona book.

```
toki pona word | equivalent in toki pona book
```

If the 'equivalent in toki pona book' column has an asterisk (*), it is not present in the toki pona book.


## References

- Sonja Lang's [Toki Pona: The Language of Good][pu]
- tokipona.net [Classic Word List (Improved!)][tpnet]
- Bruno Bord's [word list][brunobord]
- Bryan Knight's [o kama sona e toki pona!][okamasona]

[pu]: http://tokipona.org/
[tpnet]: http://tokipona.net/tp/ClassicWordList.aspx
[brunobord]: https://github.com/brunobord/toki-pona/tree/gh-pages/yaml
[okamasona]: http://tokipona.net/tp/janpije/okamasona.php


# Example Sentence Corpus
Corpus of text to be used as exemplar sentences for the Globasa dictionary. Edit this repository to make changes.

The order of files is set individually in the configuration settings for the API import examples script. You may want some high, low and last priority passage files or document files.

## Corpus File Types

### Passages

Passages are for shorter passages. Each passage share a citation. There can be lots of passage in a file. You might want different files for high priority examples vs low priority examples. Good for small quotes and smaller passages.

### MD Documents

Third is a curated document with metadata that explains how to properly cite the the document. See `doc_example.md`, as well as `doc_150_canonical_sentences.md` and `doc_posyesen_rubahe.md`. More documents like this would be best.

### Auxiliary documents

This is harder and more error prone. These documents need to have the data hard coded by the programmer. These documents are scanned and programing and the script tries to remove natlang words, but glitches may happen. Ideally, these documents would be copied and turned in to a MD Document.

These are pretty much all Grav files, and are directly loaded from the Doxo website's files.

## Order of files

The order the files are loaded is the order that example senteces are saved for each entry. This is the current order of files:

As of 2025-11-23

- doc_150_canonical_sentences.md
- doc_posyesen_rubahe.md
- https://doxo.globasa.net/eng/esey
- https://doxo.globasa.net/eng/folklorli-hikaye/fabula-fal-esopo
- https://doxo.globasa.net/eng/folklorli-hikaye/pearili-hikaye
- https://doxo.globasa.net/spa/folklorli-hikaye/alo-folklorli-hikaye
- https://doxo.globasa.net/eng/humorxey
- https://doxo.globasa.net/eng/historili-doku/ruhologili-literatur
- https://doxo.globasa.net/eng/historili-doku/globatotal-deklaradoku-tem-insanli-haki
- https://doxo.globasa.net/eng/historili-doku
- https://doxo.globasa.net/eng/mimu
- https://doxo.globasa.net/eng/lilhikaye/aselli-hikaye-in-globasa
- https://doxo.globasa.net/eng/lilhikaye/alo-hikaye
- https://doxo.globasa.net/eng/lilhikaye/hikaye-fal-vanege
- https://doxo.globasa.net/eng/lilhikaye/siri-logane-tutum
- https://doxo.globasa.net/eng/lala
- https://doxo.globasa.net/eng/inyo
- pass_general.yaml
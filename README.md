# example-sentences
Corpus of text to be used as exemplar sentences for the Globasa dictionary. Edit this repository to make changes.

When showing example sentences, files from Doxo at last (auxiliary examples). The order of documents are:

1. Override passages
2. Curated passages
3. Curated documents
4. Auxiliary documents (Doxo)

## Passages

We can create an 'override' files, where any examples in the over ride files are shows first. See `override_passages_example.yaml`.

Next is passages. If we want short passages that are curated, these will appear before most other content. See `pass_example.yaml` to see ho to format that document.

## Documents

Third is a curated document with metadata that explains how to properly cite the the document. See `doc_example.md`, as well as `doc_150_canonical_sentences.md` and `doc_posyesen_rubahe.md`. More documents like this would be best.

## Auxiliary documents

This is harder and more error prone. These documents need to have the data hard coded by the programmer. These documents are scanned and programing and the script tries to remove natlang words, but glitches may happen.

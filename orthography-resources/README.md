# FirstVoices Orthography Resources

These files represent a snapshot of basic information about BC Indigenous writing systems hosted on the FirstVoices platform. Note that many writing systems are actively updated and will change periodically, including the characters and ordering in the alphabets.

This data is useful when considering alphabetization, data normalization (including for search query input), spell-checking, testing fonts for character support, keyboard design, and many other uses. 

### Language Names and Codes

1. bc_language_metadata_2025.csv : lists basic information about BC Indigenous language names, including current names, alternate names, keywords about communities where the languages are spoken, and the BCP 47 code for each language. This file is updated periodically.

For the most up-to-date language list and context for understanding the data, see the [FPCC List of B.C. First Nations Languages (PDF)](https://fpcc.ca/resource/fpcc-list-of-languages-of-bc/)

### Orthography Data

1. firstvoices_sites_metadata_2025.csv : basic information about all included FirstVoices sites, such as the name, FirstVoices url, and language.

For each published FirstVoices site, we include the following:

1. alphabet_ordering.csv : a list of alphabet characters, in order. Note that each alphabet character may contain multiple graphemes, such as "kw" or "ll".
2. character_variants.csv : a list of any variants for the alphabet characters, which are treated as equivalent when sorting. For example, in English a variant of "a" is "A".
3. confusable_characters.csv : a list of any confusable characters for each alphabet character, which may be commonly used by mistake. For example, using "k̠" (Latin Small Letter K + Combining Low Line, \u006B\u0332) when meaning "ḵ" (Latin Small Letter K With Line Below, \u1E35).
4. ignored_characters.csv : a list of any punctuation characters that are ignored during sorting.

[Read more about these resources and their context on our Knowledge Base.](https://firstvoices.atlassian.net/wiki/spaces/FIR1/pages/1704341)

# FirstVoices Orthography Resources

These files represent a snapshot of basic information about BC Indigenous writing systems hosted on the FirstVoices platform. These reports were created in January 2025. Note that many writing systems are actively updated and will change periodically, including the characters and ordering in the alphabets.

This data is useful when considering alphabetization, data normalization (including for search query input), spell-checking, testing fonts for character support, keyboard design, and many other uses. 

### Language Names and Codes

1. languages.csv : lists basic information about BC Indigenous language names, including current names, alternate names, and keywords about communities where the languages are spoken. This is primarily drawn from the [latest language status report produced by the First Peoples' Cultural Council](https://fpcc.ca/resource/resource_type/language-status-report/).

The file also lists the BCP 47 codes for each language.

### Orthography Data

1. language_sites.csv : basic information about all included FirstVoices sites, such as the name, FirstVoices url, and language.

For each published FirstVoices site, we include the following:

1. alphabet_ordering.csv : a list of alphabet characters, in order. Note that each alphabet character may contain multiple graphemes, such as "kw" or "ll".
2. character_variants.csv : a list of any variants for the alphabet characters, which are treated the same way when alphabetizing. For example, in English a variant of "a" is "A".
3. confusable_characters.csv : a list of any confusables for the alphabet characters. 
4. ignored_characters.csv : a list of any punctuation characters that are ignored during alphabetical sorting

[Read more about these resources and their context on our Knowledge Base.](https://firstvoices.atlassian.net/wiki/spaces/FIR1/pages/1704341)

# EnglishStopWords
A dictionary of common English words, accessible as an Elm list

* Useful for processing English text
* All words are in lowercase
* All punctuation (dashes, apostrophes, etc.) is removed

## Usage

`import EnglishStopWords`

`List.filter (\x -> not (List.member x EnglishStopWords.words)) ListofWords`

`List.count EnglishStopWords.words`

# Wordle Word Dataset

This notebook compiles a datasets of words used in Wordle, both the word list and the subset of answers from the Wordle Source code, prior to *The New York Times* purchase. It supplements this dataset with additional meta data.

|field       | type     | description                                                                              |
| ---------- | -------- | ---------------------------------------------------------------------------------------- |
| word       | `string` | The word used in Wordle                                                                  |
| occurrence | `float`  | The mean prevalence in the Google Books Ngram Corpus, within the given time range.       |
| day        | `int`    | The day the Wordle word was an answer, if applicable. Non-answer words have null values. |
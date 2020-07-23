# python-bash.org-scraper
Bash.org is a delightful collection of chat quotes. On top of that, users can vote the quotes up or down. This labelling makes it an ideal database for machine learning shenanigans.

## Usage
In scrape.ipynb, use the function `scrape` as follow:
`scrape("outputfile.csv")`
or
`scrape("outputfile.json")`
depending on the prefered format.

## Format

The .csv table is formated as follows:<br>
quote_number1, score1, username1, sentence1<br>
quote_number1, score1, username1, sentence2<br>
quote_number1, score1, username2, sentence3<br>
quote_number2, score2, username3, sentence4<br>

The .json file is formated as follows:<br>
[[quote_number1, score1, [[username1, sentence1], [username1, sentence2], [username2, sentence3]]], [quote_number2, score2, [username3, sentence4]]]




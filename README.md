# Google Search Operators Cheat Sheet

| **Search Operator** | **Description**                                                                 | **Example**                          |
|---------------------|---------------------------------------------------------------------------------|--------------------------------------|
| `""`                | Search for an exact word or phrase.                                             | `"steve jobs"`                      |
| `OR`                | Search for results related to either X or Y.                                    | `jobs OR gates`                     |
| `|`                 | Functions the same as OR.                                                       | `jobs | gates`                      |
| `AND`               | Search for results related to both X and Y.                                     | `jobs AND gates`                    |
| `-`                 | Exclude results that mention a specific word or phrase.                         | `jobs -apple`                       |
| `*`                 | Acts as a wildcard, matching any word or phrase.                                | `steve * apple`                     |
| `()`                | Group multiple terms or operators to control the search logic.                  | `(ipad OR iphone) apple`            |
| `define:`           | Display the definition of a word or phrase.                                     | `define:entrepreneur`               |
| `filetype:`         | Search for specific file types (e.g., PDF).                                     | `apple filetype:pdf`                |
| `ext:`              | Same as `filetype:`.                                                            | `apple ext:pdf`                     |
| `site:`             | Limit results to a specific website or domain.                                  | `site:apple.com`                    |
| `related:`          | Find sites related to a given domain.                                           | `related:apple.com`                 |
| `intitle:`          | Search for pages with a specific word in the title.                             | `intitle:apple`                     |
| `allintitle:`       | Search for pages with all specified words in the title.                         | `allintitle:apple iphone`           |
| `inurl:`            | Search for pages with a specific word in the URL.                               | `inurl:apple`                       |
| `allinurl:`         | Search for pages with all specified words in the URL.                           | `allinurl:apple iphone`             |
| `intext:`           | Search for pages with a specific word in the body text.                         | `intext:apple iphone`               |
| `allintext:`        | Search for pages with all specified words in the body text.                     | `allintext:apple iphone`            |
| `weather:`          | Display the weather for a specific location.                                    | `weather:san francisco`             |
| `stocks:`           | Show stock information for a given ticker.                                      | `stocks:aapl`                       |
| `map:`              | Force Google to show map results for a location.                                | `map:silicon valley`                |
| `movie:`            | Search for information about a movie.                                           | `movie:steve jobs`                  |
| `in`                | Convert one unit to another.                                                    | `$329 in GBP`                       |
| `source:`           | Search for news from a specific source in Google News.                          | `apple source:the_verge`            |
| `before:`           | Find results published before a specific date.                                  | `apple before:2007-06-29`           |
| `after:`            | Find results published after a specific date.                                   | `apple after:2007-06-29`            |
| `#..#`              | Search within a range of numbers.                                               | `iphone case $50..$60`              |
| `inanchor:`         | Search for pages with specific anchor text in backlinks.                        | `inanchor:apple`                    |
| `allinanchor:`      | Search for pages with all specified words in anchor text.                       | `allinanchor:apple iphone`          |
| `AROUND(X)`         | Find pages where two terms are within X words of each other.                    | `apple AROUND(4) iphone`            |
| `loc:`              | Find results from a specific location.                                          | `loc:"san francisco" apple`         |
| `location:`         | Find news from a specific location in Google News.                              | `location:"san francisco" apple`    |
| `daterange:`        | Search within a specific date range (using Julian dates).                       | `daterange:2451127-2451327`         |

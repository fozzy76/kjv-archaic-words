# KJV archaic words and false friends

117 definitions of archaic words in the King James Bible, with 27 of them flagged as **false
friends** — words still in everyday English that meant something different in 1611.

Written for [The Almighty Jehovah](https://thealmightyjehovah.com), a free King James Bible with
narration for all 1,189 chapters. Released under CC BY 4.0 so anyone building a Bible reader,
study tool or app can use them.

## The finding this came from

The words that cost a modern reader meaning are **not** the obviously strange ones. Nobody is
misled by *wot* or *thee* — a reader hits those, notices, and looks them up.

The costly ones are the words still in common use whose sense has shifted. A reader passes straight
over them **believing they understood**, and the verse quietly means something else.

| word | occurrences in the KJV | what it actually means |
| --- | ---: | --- |
| meat | 290 | food of any kind, not flesh specifically |
| corn | 102 | grain of any kind — wheat or barley, not maize |
| suffer | 96 | to allow or permit |
| rent | 66 | torn |
| charity | 28 | love — the self-giving kind |

*"Suffer the little children to come unto me"* is not about suffering. *"Charity suffereth long"*
is not about charity in the modern sense, twice over in four words.

## What is in here

| file | what it is |
| --- | --- |
| `kjv-archaic-words.json` | the full set, with definitions and the false-friend flag |
| `kjv-archaic-words.csv` | the same as a spreadsheet |

Each entry carries the word, a plain-English definition, and whether it is a false friend.

## How the words were chosen

**Data driven from the text itself, not copied from an existing list.**

Every one of the 1,189 chapters was scanned. 213 candidate words were tested against the actual
text, 204 were found, and the resulting 6,199 occurrences were ranked by frequency. The 117 entries
here cover **93% of every archaic-word occurrence in the KJV** and **100% of the 40 most frequent**.

That ordering is the point. A list assembled by intuition covers the memorable words; a list
assembled by frequency covers the words a reader actually meets.

## Why the definitions are original

There is no cleanly licensed archaic-KJV-word dataset. The lists in circulation are editorial
compilations with no open license, so using them would be taking someone else's work.

Webster's 1828 *is* public domain, but it answers in 200-year-old prose that is frequently harder
than the verse it is explaining — which is no help to the reader who needed it.

So these definitions were written for this dataset. They are short, modern, and aimed at the person
reading the verse right now.

## License

**CC BY 4.0.** Use them anywhere, including commercially. The one condition is attribution:
credit [The Almighty Jehovah](https://thealmightyjehovah.com).

## What is deliberately not here

The King James text itself is public domain and available in better form elsewhere — see
[awesome-bible-data](https://github.com/jcuenod/awesome-bible-data).

Cross-reference data is **not** included. The set used on the site comes from someone else under
CC BY and is theirs to distribute, not ours.

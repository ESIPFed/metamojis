# Why metamojis?
Data flags are commonly used throughout the earth sciences to communicate data quality and provide other helpful information to users.

SeaDataNet, for instance, uses numeric codes to convey information about data quality:

- 0 – No QC
- 1 – Good value
- 2 – Probably good
- 4 – Bad value
- 6 – Below Detection

Similarly, Andrews LTER uses simple letter-based codes.

- A – Accepted
- E – Estimated
- M – Missing
- Q – Questionable

But what if we could make things a little more exciting? What if instead of using numbers and letters, we used … emojis 😛⁉

While it may seem silly at first, emojis provide a number of attractive properties.

## Self-describing:
Unlike letter and number-based codes, emojis are immediately interpretable. Even without a data dictionary, users can get the gist of what an emoji-based flag means. A user who sees a 😀 flag for instance, might guess that it means good data quality, whereas 🙁 means poor data quality, and so on.

## Unicode:
Each emoji is a unique character in the unicode standard. This means that emojis can be used in any context where unicode is supported (basically everywhere on the internet). Moreover, this feature makes emojis easy to search, parse or index.

## Lightweight:
Emojis can describe relatively complex concepts using a single character. At 1-4 bytes per UTF-8 character, an emoji is significantly more efficient than a full textual description. For instance, using 🔬instead of “below detection” would quarter the number of bytes required.

## Accessible:
Let’s face it, using emojis makes the task of flagging and annotating data a lot more fun! And at the risk of sounding old, it could also help to get a new generation of earth scientists excited about metadata.

# Registry

See the registry of standard metamojis [here](https://github.com/ESIPFed/metamojis/blob/master/registry.org).

# freq

## About
This is a simple cryptanalytic frequency analysis tool that uses [english character digrams](https://en.wikipedia.org/wiki/Bigram) as a probabilistic model for scoring ByteStrings according to their randomness (0..1, 0 being the most random, 1 being the least random).

## Uses
I currently use this to validate domain names, and so the training data available consists of about 6.5 Megabytes of Public Domain 19th and 20th century English novels. You can feed any training data you wish to 'freq' to achieve different results.

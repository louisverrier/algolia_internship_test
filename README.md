# algolia_internship_test
Internship technical test

I had two big decisions in how I wanted to process the data: first I decided to separate a query into the words forming it, and counting occurences of each word. Second I decided to take into account only words with at least 4 letters to avoid meaningless results. That is obviously entirely customizable. I also decided not to load the entire dataset at once since it made my PC slow to a crawl! End result: a vocabulary of around 120 thousand words. I'm not happy about the processing time, but with the limited time given, I didn't have a better idea than to keep all words: most of the time is spent searching words in a list.

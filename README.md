# Towards Automatic Discursive News Values Analysis

What is deemed worthy of being "news"? How is newsworhyness constructed?

"news values" such as Timeliness, Negativity, Impact, Superlativeness, Eliteness, Consonance, and others can be thought of as high-level "features" of a particular news report or article. News values are seen as values that exist in and are constructed through discourse [(Bednarek, Caple 2014)](http://das.sagepub.com/content/25/2/135.abstract). Can we extract these with existing Natural Language Processing and Machine Vision tools?

["Discursive News Values Analysis"](http://www.newsvaluesanalysis.com/what-is-dnva/) outlines a set of news values or "features" of newsworthyness.

The task is to extract / tag / annotate content with these news values. Or at least help automate some parts. Some of these are easier than others, some may already be "solved" as in: have available implementations that work well in practice. 

For example: 

* Timeliness: Temporal taggers like [HeidelTime](https://github.com/HeidelTime/heideltime) are quite good, we don't know if it's good enough for this exact task, but it's there.

* Negativity / Positivity: Sentiment Analysis approaches could apply here. Tagging Negativity / Positivity _newsvalues_ seems like a different problem to just scoring text as positive or negative.



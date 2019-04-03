# SemEval 2017 Task 5 - Subtask 2 "Fine-Grained Sentiment Analysis on Financial News Headlines"

This repository contains the data and source code for subtask 2 "News Headlines" of task 5 in SemEval 2017, "Fine-Grained Sentiment Analysis on Financial Microblogs and News" (see [task website](http://alt.qcri.org/semeval2017/task5/)).
It consists of a collection of financially relevant news headlines which have been annotated for fine-grained sentiment. 

## Annotations

Each message in Headline_Trialdata.json is annotated with the following information:

1. `id`: unique ID of the instance in our data
2. `title`: text content of the headline
3. `company`: company that the `sentiment` relates to
4. `sentiment`: a floating point value between `-1` (very bearish/negative) and `1` (very bullish/positive) denoting the sentiment expressed towards `company`. `0` denotes neutral sentiment.

## Licenses

The annotations are licensed under the [Creative Commons Attribution-Non-Commercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.
Please cite the SemEval 2017 task description paper for task 5 (once available) when using this dataset.

If you are interested in commercial use of these data, please [contact the SSIX consortium|http://ssix-project.eu/contact-us/].

## Acknowledgements

These resources were created in the context of the [SSIX project](http://ssix-project.eu/).
This project has received funding from the 
[European Union's Horizon 2020](https://ec.europa.eu/programmes/horizon2020/) 
research and innovation programme under grant agreement No 645425.



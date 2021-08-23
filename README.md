# Tweets_sentiment_analysis

This script allows you to evaluate the sentiment of tweets in English using 4 dictionaries:

1) General Inquirer (Harvard IV-4 and Laswell dictionaries) Financial vocabulary, includes 3695 negative words and 2550 positive words. Pysentiment library. 
Authors: (Stone P., Dunphy D.C., Smith M.S., 1966)

2) Loughran & McDonald Dictionary of Finance includes 2350 negative words and 352 positive words. Pysentiment library Credit: 
Authors: (Loughran & Mcdonald, 2011)

3) Vader. Sentiment Classifier at the Sentiment Level 
Authors: (Hutto & Gilbert, 2014)

4) SenticNet 6.0. A publicly available semantic and affective resource for analyzing opinions at the concept level. Sentic Library 
Authors: (Cambria et al., 2020)

The arrays are preliminarily cleared of links, hashtags, etc., then the text is evaluated sequentially using dictionaries. Equal weights are used as averaging for calculating the daytime sentiment, there is an option to use the number of retweets of a single tweet as the share of this tweet in the calculation of the daytime sentiment.


#  Оценка тональности твитов с помощью словарей

Данный скрипт позволяет оценить тональность твитов на английском языке по 4 словарям:
1) General Inquirer (словари Harvard IV-4 и Laswell)
Финансовый словарь, включает 3695 негативных слов и 2550 позитивных слов. Библиотека pysentiment.
Авторы: (Stone P., Dunphy D.C., Smith M.S., 1966)

2) Loughran &McDonald Финансовый словарь, включает 2350 негативных слов и 352 позитивных слова. Библиотека pysentiment
Авторы: (Loughran & Mcdonald, 2011)

3) Vader. Классификатор настроений на уровне предложения
Авторы: (Hutto & Gilbert, 2014)

4) SenticNet 6.0. Общедоступный семантический и аффективный ресурс для анализа мнений на уровне концепций. Библиотека sentic
Авторы: (Cambria et al., 2020)

Предварительно массивы очищаются от ссылок,хэштегов и проч., затем текст оценивается последовательно по словарям. В качестве усреднения для расчёта дневной тональности применяются равные веса, есть вариант использования числа ретвитов отдельного твита в качестве доли этого твита в расчёте дневной тональности.

# nlp-problem

### Problem
Please create a NLP model to predict news category with headline as input.

### About data file
The file contains 202,372 records. Each json record contains following attributes:

- *category*: Category article belongs to
- *headline*: Headline of the article
- *authors*: Person authored the article
- *link*: Link to the post
- *short_description*: Short description of the article
- *date*: Date the article was published

Eg.
<pre>
<code>
{
    "category": "SPORTS",
    "headline": "Dwight Howard Rips Teammates After Magic Loss To Hornets", "authors": "",
    "link": "https://www.huffingtonpost.com/entry/dwight-howard-rips-teammates-magic-hornets_us_5bb69b24e4b097869fd1b331",
    "short_description": "The five-time all-star center tore into his teammates Friday night after Orlando committed 23 turnovers en route to losing",
    "date": "2012-01-28"
}
</code>
</pre>

### Solution
- Code to process data and training model
- Your thoughts on how to solve the problem
- Code to predict.
    - Input is headline of news got from <a href="https://www.huffpost.com/">huffpost</a>.
    - Output will be predicted category

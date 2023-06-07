## James Joyce's *Ulysses*: A Sentiment Analysis

<p><img style="float: right ; margin: 5px 20px 5px 10px; width: 45%" src="https://github.com/MyreLab/ulysses-sentiment-analysis/blob/main/datasets/ulysses_img.jpg?raw=true"></p>

<blockquote>
  <p><i>
  "Stately, plump Buck Mulligan came from the stairhead, bearing a bowl of lather on which a mirror and a razor lay crossed. A yellow dressinggown, ungirdled, was sustained gently behind him on the mild morning air. He held the bowl aloft and intoned: Introibo ad altare Dei."
    - James Joyce
</i></p>
</blockquote>

<p>In this project, I scraped the novel <i>Ulysses</i> from the website <a href="https://www.gutenberg.org/">Project Gutenberg</a> using the Python package <code>requests</code>. Then, I extracted and tokenized the text from html using <code>BeautifulSoup</code> and <code>nltk</code>. Finally, I dived into a sentiment analysis of 30 characters from the novel using <code>nltk</code> and <code>Vader</code>.</p>

